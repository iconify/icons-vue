<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-5tx90gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o-5tx90gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:junk-car" /></template>
