<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3f71owim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3f71owim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:git-commit-vertical" /></template>
