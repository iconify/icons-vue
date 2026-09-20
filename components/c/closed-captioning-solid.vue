<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftna4mboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ftna4mboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:closed-captioning-solid" /></template>
