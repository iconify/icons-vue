<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idstbwbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="idstbwbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:github" /></template>
