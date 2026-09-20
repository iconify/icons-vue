<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fflkcy2nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fflkcy2nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:front-square-filled" /></template>
