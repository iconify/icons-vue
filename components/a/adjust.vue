<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl87nh5pk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cl87nh5pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:adjust" /></template>
