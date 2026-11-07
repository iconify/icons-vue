<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbgenzzof.css';
import '../../css/f/fu36ikuad.css';
import '../../css/u/u6-7e5-on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbgenzzof"/><path clip-rule="evenodd" class="fu36ikuad"/><path clip-rule="evenodd" class="u6-7e5-on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:inbox-line-bold" /></template>
