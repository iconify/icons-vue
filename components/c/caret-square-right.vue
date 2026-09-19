<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp6scbbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="fp6scbbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:caret-square-right" /></template>
