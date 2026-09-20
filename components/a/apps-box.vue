<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltkf0bsxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltkf0bsxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:apps-box" /></template>
