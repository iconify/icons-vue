<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_ewppbtl.css';
import '../../css/u/uqlamj4tr.css';
import '../../css/v/vtfwic-qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_ewppbtl"/><circle class="uqlamj4tr"/><path class="vtfwic-qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:calendar-outline" /></template>
