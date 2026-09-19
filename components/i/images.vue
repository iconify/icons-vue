<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r97dsrqiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="r97dsrqiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:images" /></template>
