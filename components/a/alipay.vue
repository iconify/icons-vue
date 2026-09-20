<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx1b4ebgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx1b4ebgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:alipay" /></template>
