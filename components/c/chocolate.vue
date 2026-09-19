<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs-0on4wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":960};
const content = `<path class="bs-0on4wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:chocolate" /></template>
