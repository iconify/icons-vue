<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo1qmrsci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bo1qmrsci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campsite-on-pier-in-water" /></template>
