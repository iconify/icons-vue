<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waq_d7rbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="waq_d7rbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:flask-florence-fill" /></template>
