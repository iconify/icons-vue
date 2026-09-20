<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5wxbs7ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g5wxbs7ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:hot-drink-cup" /></template>
