<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2cda_lwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z2cda_lwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-commit-bold" /></template>
