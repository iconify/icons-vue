<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_29zdb8m.css';
import '../../css/e/ess3czbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_29zdb8m"/><path clip-rule="evenodd" class="ess3czbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-mark-bold" /></template>
