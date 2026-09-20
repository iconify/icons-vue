<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi4e96bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi4e96bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:git-repository-commits-line" /></template>
