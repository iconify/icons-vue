<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7_lms_6w.css';
import '../../css/v/vbpiltbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="t7_lms_6w"/><path class="vbpiltbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:gallery-horizontal-end-filled" /></template>
