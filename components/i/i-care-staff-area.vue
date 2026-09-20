<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v155xpb1d.css';
import '../../css/x/x7ektt91o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="v155xpb1d"/><path class="x7ektt91o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-care-staff-area" /></template>
