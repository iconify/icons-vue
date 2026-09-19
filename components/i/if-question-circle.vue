<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqeas2b2i.css';
import '../../css/k/ks-k4jbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqeas2b2i"/><path class="ks-k4jbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:if-question-circle" /></template>
