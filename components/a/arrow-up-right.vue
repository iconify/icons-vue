<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1byibb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1byibb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-up-right" /></template>
