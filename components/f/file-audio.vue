<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f71pecfek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f71pecfek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-audio" /></template>
