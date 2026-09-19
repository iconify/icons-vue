<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf6tsfb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="jf6tsfb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:dice-five" /></template>
