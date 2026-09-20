<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgpa-chjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jgpa-chjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:control-checkbox" /></template>
