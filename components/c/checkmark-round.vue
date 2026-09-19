<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1p4mubec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h1p4mubec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:checkmark-round" /></template>
