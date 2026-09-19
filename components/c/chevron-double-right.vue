<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/furgsjbhc.css';
import '../../css/c/cn0c-05yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="furgsjbhc"/><path class="cn0c-05yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:chevron-double-right" /></template>
