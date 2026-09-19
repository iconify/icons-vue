<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvh2v--5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":717};
const content = `<path class="bvh2v--5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:link" /></template>
