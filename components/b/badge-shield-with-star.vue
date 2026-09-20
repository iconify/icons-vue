<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_aqy6b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q_aqy6b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:badge-shield-with-star" /></template>
