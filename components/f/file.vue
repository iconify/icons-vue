<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3p7xnusk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":597,"height":717};
const content = `<path class="v3p7xnusk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:file" /></template>
