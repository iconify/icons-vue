<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w86rhlbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":646};
const content = `<path class="w86rhlbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:dashboard" /></template>
