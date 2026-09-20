<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a61u5nbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a61u5nbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lion-and-question-mark" /></template>
