<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvj0xqs8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cvj0xqs8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:github-alt" /></template>
