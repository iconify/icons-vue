<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzl8onbyv.css';
import '../../css/a/af2-mdbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fzl8onbyv"/><path class="af2-mdbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:js-error" /></template>
