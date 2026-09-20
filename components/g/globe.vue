<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsz3vzbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsz3vzbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:globe" /></template>
