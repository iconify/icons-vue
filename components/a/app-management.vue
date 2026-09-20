<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5t4qho-n.css';
import '../../css/e/e3e-l4bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j5t4qho-n ouiIcon__fillSecondary"/><path class="e3e-l4bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-management" /></template>
