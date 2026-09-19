<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rztsgpblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":679};
const content = `<path class="rztsgpblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:bad" /></template>
