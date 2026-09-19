<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdig666dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":769,"height":1024};
const content = `<path class="sdig666dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:h-upper-case" /></template>
