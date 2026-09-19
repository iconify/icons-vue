<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptlw2acps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ptlw2acps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:canvasrulers" /></template>
