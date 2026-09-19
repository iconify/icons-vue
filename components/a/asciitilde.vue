<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k27hhsbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":508,"height":614};
const content = `<path class="k27hhsbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:asciitilde" /></template>
