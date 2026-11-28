<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en-vohbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en-vohbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:git-branch-solid" /></template>
