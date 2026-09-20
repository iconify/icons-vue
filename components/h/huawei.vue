<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4hy-p3tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4hy-p3tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:huawei" /></template>
