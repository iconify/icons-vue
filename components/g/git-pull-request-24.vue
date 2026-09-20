<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajh12op2y.css';
import '../../css/q/qtmpeuosr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajh12op2y"/><path class="qtmpeuosr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-pull-request-24" /></template>
