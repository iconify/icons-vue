<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7bk0z64w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w7bk0z64w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:boulder3" /></template>
