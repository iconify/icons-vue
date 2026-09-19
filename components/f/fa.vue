<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obj4ptb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1504,"height":1792};
const content = `<path class="obj4ptb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:fa" /></template>
