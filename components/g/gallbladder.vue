<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrnyv_a6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jrnyv_a6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gallbladder" /></template>
