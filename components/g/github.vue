<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e--4hqbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="e--4hqbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:github" /></template>
