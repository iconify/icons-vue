<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kyfjcqbwm.css';
import '../../css/s/slcgv9bsj.css';
import '../../css/v/vaxyf-bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kyfjcqbwm"/><path class="slcgv9bsj"/><path class="vaxyf-bcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:chart-area-duotone" /></template>
