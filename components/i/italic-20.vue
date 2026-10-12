<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaa05bc3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jaa05bc3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:italic-20" /></template>
