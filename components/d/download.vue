<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q26m2lrpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q26m2lrpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:download" /></template>
