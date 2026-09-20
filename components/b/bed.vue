<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb_1xkbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vb_1xkbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bed" /></template>
