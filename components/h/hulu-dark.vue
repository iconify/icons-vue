<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3p-zvbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o3p-zvbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hulu-dark" /></template>
