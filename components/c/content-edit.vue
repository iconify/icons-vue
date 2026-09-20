<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmmt4yb1s.css';
import '../../css/o/omfzgbbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mmmt4yb1s"/><path class="omfzgbbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-edit" /></template>
