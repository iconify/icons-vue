<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7tooesbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="z7tooesbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:itunes-note" /></template>
