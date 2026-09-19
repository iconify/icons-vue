<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw6emmb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cw6emmb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:exclamation-circle" /></template>
