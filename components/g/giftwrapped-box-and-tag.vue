<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdu7zo3md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tdu7zo3md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:giftwrapped-box-and-tag" /></template>
