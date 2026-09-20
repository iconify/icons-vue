<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3bp1l9tp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y3bp1l9tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:board-heavy-rail" /></template>
