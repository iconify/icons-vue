<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o91i2d-pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o91i2d-pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:beef-solid" /></template>
