<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_hnlpuwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q_hnlpuwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:cachyos" /></template>
