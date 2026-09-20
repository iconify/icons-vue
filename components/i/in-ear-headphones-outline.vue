<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8yt0_gac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q8yt0_gac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:in-ear-headphones-outline" /></template>
