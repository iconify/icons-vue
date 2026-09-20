<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkzximbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qkzximbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:droplet-above-water" /></template>
