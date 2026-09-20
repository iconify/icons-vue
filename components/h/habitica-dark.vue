<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unyc-m8wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="unyc-m8wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:habitica-dark" /></template>
