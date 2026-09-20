<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfeaq_g8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xfeaq_g8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:diamond-outline" /></template>
