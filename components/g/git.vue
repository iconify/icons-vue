<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnip18ypu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jnip18ypu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:git" /></template>
