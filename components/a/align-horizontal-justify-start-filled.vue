<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvg_1-o8n.css';
import '../../css/g/gqj_zqq9u.css';
import '../../css/j/jw_3-cczy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="uvg_1-o8n"/><rect class="gqj_zqq9u"/><path class="jw_3-cczy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:align-horizontal-justify-start-filled" /></template>
