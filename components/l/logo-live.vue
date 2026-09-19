<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6hh-zbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c6hh-zbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:logo-live" /></template>
