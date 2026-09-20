<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g98dd5zxh.css';
import '../../css/e/evjd1k6-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="g98dd5zxh"/><path class="evjd1k6-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-ultrasound" /></template>
