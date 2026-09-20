<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw0c2llzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bw0c2llzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:alcohol-shop" /></template>
