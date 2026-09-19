<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwb4r1b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="jwb4r1b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:magnet" /></template>
