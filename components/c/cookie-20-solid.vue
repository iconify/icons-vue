<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz1unabkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cz1unabkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cookie-20-solid" /></template>
