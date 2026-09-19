<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdx__9a1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bdx__9a1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-merge-left-filled" /></template>
