<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dll7k3y3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dll7k3y3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:italic-outline" /></template>
