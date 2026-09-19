<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpgos0b_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":676};
const content = `<path class="jpgos0b_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:comment" /></template>
