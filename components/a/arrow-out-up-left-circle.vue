<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbtdtbc5w.css';
import '../../css/i/ifoopobcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbtdtbc5w"/><path class="ifoopobcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-up-left-circle" /></template>
