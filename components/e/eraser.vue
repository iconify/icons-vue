<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f378ucbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f378ucbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:eraser" /></template>
