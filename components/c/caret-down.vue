<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly4ps1k1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ly4ps1k1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:caret-down" /></template>
