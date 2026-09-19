<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6t4h-brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="x6t4h-brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:gem" /></template>
