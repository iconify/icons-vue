<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewhgnkbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ewhgnkbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:folder-open-16" /></template>
