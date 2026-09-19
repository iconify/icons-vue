<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qau_99whd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="qau_99whd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:linode" /></template>
