<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyq_t3ubt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyq_t3ubt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:appsignal" /></template>
