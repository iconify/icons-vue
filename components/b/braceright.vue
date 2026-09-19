<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r08ed1f0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":289,"height":960};
const content = `<path class="r08ed1f0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:braceright" /></template>
