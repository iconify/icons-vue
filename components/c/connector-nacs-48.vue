<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xagjmlbpr.css';
import '../../css/x/xtdm6g52u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xagjmlbpr"/><path class="xtdm6g52u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-nacs-48" /></template>
