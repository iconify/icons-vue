<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajmjvabeq.css';
import '../../css/a/acfb3gbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":208,"height":92};
const content = `<path class="ajmjvabeq"/><path class="acfb3gbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:amul-info" /></template>
