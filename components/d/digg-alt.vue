<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hubdunbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":464};
const content = `<path class="hubdunbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:digg-alt" /></template>
