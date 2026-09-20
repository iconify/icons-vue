<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqntgacbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqntgacbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:local-see" /></template>
