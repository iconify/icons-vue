<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds4gxrb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ds4gxrb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-restaurant" /></template>
