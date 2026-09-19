<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_top7b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x_top7b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlevine" /></template>
