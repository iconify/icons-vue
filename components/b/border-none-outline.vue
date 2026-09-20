<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kei2h4l7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kei2h4l7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:border-none-outline" /></template>
