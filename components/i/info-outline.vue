<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd_6cr3kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xd_6cr3kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:info-outline" /></template>
