<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzri54b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vzri54b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bust-on-plinth" /></template>
