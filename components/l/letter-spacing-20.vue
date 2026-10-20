<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq0yvabzs.css';
import '../../css/u/ura9qubce.css';
import '../../css/u/ufqapwbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jq0yvabzs"/><path class="ura9qubce"/><path class="ufqapwbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:letter-spacing-20" /></template>
