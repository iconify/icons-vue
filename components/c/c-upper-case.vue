<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmtfpgbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":721,"height":776};
const content = `<path class="bmtfpgbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:c-upper-case" /></template>
