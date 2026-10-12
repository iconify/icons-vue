<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwg583h1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bwg583h1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:emoji-upset-fill-20" /></template>
