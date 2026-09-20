<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx9h71b0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx9h71b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:copy-solid" /></template>
