<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py6-88b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="py6-88b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:embed-audio" /></template>
