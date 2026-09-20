<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff99hubzr.css';
import '../../css/o/omxh1nh0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff99hubzr"/><path class="omxh1nh0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:design-tool-compass-bold" /></template>
