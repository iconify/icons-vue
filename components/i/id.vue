<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxljl4b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vxljl4b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:id" /></template>
