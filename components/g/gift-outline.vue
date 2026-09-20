<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9sxm0bwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a9sxm0bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:gift-outline" /></template>
