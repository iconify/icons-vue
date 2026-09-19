<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfj0fgbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hfj0fgbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:code-slash-outline" /></template>
