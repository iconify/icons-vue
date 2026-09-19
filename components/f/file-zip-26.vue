<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl7tz6c7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":26};
const content = `<path class="rl7tz6c7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-zip-26" /></template>
