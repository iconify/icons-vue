<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdqvevzmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mdqvevzmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:bicycle-14" /></template>
