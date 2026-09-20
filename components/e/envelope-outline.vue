<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_g6s6b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y_g6s6b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:envelope-outline" /></template>
