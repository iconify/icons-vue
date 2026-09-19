<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayh6ug0lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ayh6ug0lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hamsa" /></template>
