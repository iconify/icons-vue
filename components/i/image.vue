<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc75m8d8n.css';
import '../../css/r/rkf9r95ba.css';
import '../../css/g/gc3ocublh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="mc75m8d8n"/><path class="rkf9r95ba"/><path class="gc3ocublh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:image" /></template>
