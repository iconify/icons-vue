<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v17n67bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v17n67bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:format-audio" /></template>
