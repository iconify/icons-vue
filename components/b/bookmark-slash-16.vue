<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0h--2odr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z0h--2odr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:bookmark-slash-16" /></template>
