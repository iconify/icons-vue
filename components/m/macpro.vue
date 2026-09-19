<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp3xrcb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="vp3xrcb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:macpro" /></template>
