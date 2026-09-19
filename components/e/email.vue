<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfo1k5b-e.css';
import '../../css/u/u0q_e1bqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":14};
const content = `<path class="sfo1k5b-e"/><path class="u0q_e1bqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:email" /></template>
