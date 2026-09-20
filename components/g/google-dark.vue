<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c24govbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c24govbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-dark" /></template>
