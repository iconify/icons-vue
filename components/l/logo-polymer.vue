<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo87m9b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jo87m9b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-polymer" /></template>
