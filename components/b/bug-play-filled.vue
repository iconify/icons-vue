<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0wlds3qh.css';
import '../../css/l/lda5p5b_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0wlds3qh"/><path clip-rule="evenodd" class="lda5p5b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bug-play-filled" /></template>
