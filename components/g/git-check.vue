<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5094f7ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5094f7ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-check" /></template>
