<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjxba3boa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjxba3boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-commit-fill" /></template>
