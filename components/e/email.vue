<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lad5g161t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lad5g161t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:email" /></template>
