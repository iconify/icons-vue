<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z22a7qbic.css';
import '../../css/a/ak65cgiry.css';
import '../../css/n/n7_q_sbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-a z22a7qbic"/><path class="ak65cgiry wm-k"/><path class="n7_q_sbsa wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:chart-line" /></template>
