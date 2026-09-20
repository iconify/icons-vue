<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdf1evbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jdf1evbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:commento-dark" /></template>
