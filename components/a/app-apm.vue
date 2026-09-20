<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krpjbebjv.css';
import '../../css/k/krmzf_byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="krpjbebjv"/><path class="krmzf_byg ouiIcon__fillSecondary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-apm" /></template>
