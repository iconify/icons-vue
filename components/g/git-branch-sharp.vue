<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oawoxwbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oawoxwbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-branch-sharp" /></template>
