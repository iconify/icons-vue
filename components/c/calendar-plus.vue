<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox5bagm_m.css';
import '../../css/n/nf_ef62wo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox5bagm_m"/><path class="nf_ef62wo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:calendar-plus" /></template>
