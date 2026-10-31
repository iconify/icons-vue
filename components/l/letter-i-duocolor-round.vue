<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0n2rp83n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0n2rp83n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-i-duocolor-round" /></template>
