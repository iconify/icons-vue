<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sykjxo4sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sykjxo4sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:blender-phone" /></template>
