<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfjhs7b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sfjhs7b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:africa-and-madagascar" /></template>
