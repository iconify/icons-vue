<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyd4gcyqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wyd4gcyqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:diamond-two" /></template>
