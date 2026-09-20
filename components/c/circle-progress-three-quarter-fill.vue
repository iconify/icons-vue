<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qefui5bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qefui5bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-progress-three-quarter-fill" /></template>
