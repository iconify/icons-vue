<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v77_sjkpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v77_sjkpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-commit-horizontal-fill" /></template>
