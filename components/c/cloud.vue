<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj1k-xb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bj1k-xb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:cloud" /></template>
