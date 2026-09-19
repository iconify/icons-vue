<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0cdwoxlc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0cdwoxlc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:git-commit" /></template>
