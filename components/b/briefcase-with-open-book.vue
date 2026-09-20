<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn30zibei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gn30zibei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:briefcase-with-open-book" /></template>
