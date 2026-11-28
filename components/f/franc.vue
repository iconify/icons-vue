<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q64uyfelw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q64uyfelw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:franc" /></template>
