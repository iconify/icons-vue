<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/berhd0bqr.css';
import '../../css/u/ue40k2bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="berhd0bqr"/><path class="ue40k2bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bell-minus-filled" /></template>
