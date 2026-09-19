<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1jzv7brt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="c1jzv7brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:folder-open-outline" /></template>
