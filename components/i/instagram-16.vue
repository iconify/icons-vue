<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d95zib8im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d95zib8im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:instagram-16" /></template>
