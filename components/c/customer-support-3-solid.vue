<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn6uicxet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vn6uicxet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:customer-support-3-solid" /></template>
