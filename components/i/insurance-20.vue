<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bitd75egg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bitd75egg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:insurance-20" /></template>
