<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbr_dz7cx.css';
import '../../css/q/q8pmglblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kbr_dz7cx"/><path class="q8pmglblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:checkmark-filled" /></template>
