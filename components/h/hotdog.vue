<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1_175rrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n1_175rrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hotdog" /></template>
