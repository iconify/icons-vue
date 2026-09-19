<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgfcvm6ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="cgfcvm6ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:filmstrip" /></template>
