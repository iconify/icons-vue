<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hotf6gb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hotf6gb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-clockwise-circle-fill" /></template>
