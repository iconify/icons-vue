<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9-abobfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j9-abobfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:energy" /></template>
