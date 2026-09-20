<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q53hz-bxg.css';
import '../../css/z/z8ovlk4ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q53hz-bxg"/><path class="z8ovlk4ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:credit-card" /></template>
