<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js-p82bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="js-p82bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kapowarr-dark" /></template>
