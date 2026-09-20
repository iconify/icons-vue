<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxys06b2v.css';
import '../../css/k/kju8o8xdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sxys06b2v"/><path class="kju8o8xdi ouiIcon__fillSecondary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-logs" /></template>
