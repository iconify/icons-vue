<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd0_zwbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="kd0_zwbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:close-xs" /></template>
