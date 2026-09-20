<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2_waf_pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2_waf_pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:fullscreen-exit-fill" /></template>
