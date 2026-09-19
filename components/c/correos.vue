<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4i1bbb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4i1bbb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:correos" /></template>
