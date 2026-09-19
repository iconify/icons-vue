<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvxhx3bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hvxhx3bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:file-fragment" /></template>
