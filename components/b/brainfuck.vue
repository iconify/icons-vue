<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwsradb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jwsradb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:brainfuck" /></template>
