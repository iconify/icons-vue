<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ianouabio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ianouabio primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:git-fork-duotone" /></template>
