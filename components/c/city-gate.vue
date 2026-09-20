<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enjjb4y7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="enjjb4y7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:city-gate" /></template>
