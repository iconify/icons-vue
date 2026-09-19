<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbf7t6bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bbf7t6bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:everplaces" /></template>
