<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5z0mxbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="z5z0mxbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:bed" /></template>
