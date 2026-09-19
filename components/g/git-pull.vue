<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fria-632b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fria-632b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:git-pull" /></template>
