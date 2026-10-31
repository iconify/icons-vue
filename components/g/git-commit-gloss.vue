<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu_un6b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu_un6b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-commit-gloss" /></template>
