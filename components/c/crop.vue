<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i64wucb0q.css';
import '../../css/q/qryw2o0qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i64wucb0q"/><path class="qryw2o0qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:crop" /></template>
