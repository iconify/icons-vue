<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzur78bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="fzur78bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:bicycle-11" /></template>
