<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyvmq433f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dyvmq433f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-with-euro" /></template>
