<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnj1zubho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fnj1zubho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:book-with-heavy-six-point-asterisk" /></template>
