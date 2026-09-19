<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy7ceab4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dy7ceab4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bookmark-slash-20-solid" /></template>
