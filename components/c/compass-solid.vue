<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crnq79b9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crnq79b9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:compass-solid" /></template>
