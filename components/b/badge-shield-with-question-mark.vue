<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do_ni8ani.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="do_ni8ani"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:badge-shield-with-question-mark" /></template>
