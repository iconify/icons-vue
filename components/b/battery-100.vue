<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7qew4bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="b7qew4bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:battery-100" /></template>
