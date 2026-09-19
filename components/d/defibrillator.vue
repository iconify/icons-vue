<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3sab5e0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r3sab5e0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:defibrillator" /></template>
