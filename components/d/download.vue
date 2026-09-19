<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e__0vq20f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e__0vq20f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:download" /></template>
