<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9pggfb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="i9pggfb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:certificate" /></template>
