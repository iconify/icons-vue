<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saa5oybee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="saa5oybee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hockey-puck" /></template>
