<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wff71wb4h.css';
import '../../css/e/ek_fw-biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wff71wb4h"/><path class="ek_fw-biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-superset-dark" /></template>
