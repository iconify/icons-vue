<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qplp73bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qplp73bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:content-save-alert" /></template>
