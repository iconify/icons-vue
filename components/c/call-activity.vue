<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnd4yka7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<rect transform="translate(0 947.638)" class="lnd4yka7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:call-activity" /></template>
