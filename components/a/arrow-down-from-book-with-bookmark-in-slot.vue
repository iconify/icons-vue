<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de0jk_bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="de0jk_bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-down-from-book-with-bookmark-in-slot" /></template>
