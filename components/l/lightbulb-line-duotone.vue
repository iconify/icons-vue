<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zvrx42i3v.css';
import '../../css/z/zfvp08v5a.css';
import '../../css/h/h54ylcbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zvrx42i3v"/><path class="zfvp08v5a"/><path class="h54ylcbtg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lightbulb-line-duotone" /></template>
