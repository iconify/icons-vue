<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulblegbmg.css';
import '../../css/f/fszydxb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulblegbmg"/><path class="fszydxb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:lightbulb-off-filled" /></template>
