<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9xvnhbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="o9xvnhbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:kanji-utage" /></template>
