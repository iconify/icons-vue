<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnli30bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jnli30bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:document-management" /></template>
