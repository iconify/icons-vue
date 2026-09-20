<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_5pycbka.css';
import '../../css/b/bjttmb9ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="h_5pycbka"/><path class="bjttmb9ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:bikini" /></template>
