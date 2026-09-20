<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsp1cjdax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gsp1cjdax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:embassy" /></template>
