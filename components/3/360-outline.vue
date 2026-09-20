<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz7cydblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wz7cydblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:360-outline" /></template>
