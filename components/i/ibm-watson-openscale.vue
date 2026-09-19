<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzh6_5bci.css';
import '../../css/t/t987snbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vzh6_5bci"/><path class="t987snbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-watson-openscale" /></template>
