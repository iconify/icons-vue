<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjjac2bhg.css';
import '../../css/e/egvbavgae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjjac2bhg"/><path clip-rule="evenodd" class="egvbavgae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:copy-check-outline" /></template>
