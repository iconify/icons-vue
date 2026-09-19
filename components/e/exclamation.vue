<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-kyixbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":512};
const content = `<path class="q-kyixbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:exclamation" /></template>
