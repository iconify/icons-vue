<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd9ajlbga.css';
import '../../css/v/vdnqjebwm.css';
import '../../css/x/xj894begb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle r="1.5" class="qd9ajlbga"><animate attributeName="r" dur="0.75s" repeatCount="indefinite" values="1.5;3;1.5"/></circle><circle r="3" class="vdnqjebwm"><animate attributeName="r" dur="0.75s" repeatCount="indefinite" values="3;1.5;3"/></circle><circle r="1.5" class="xj894begb"><animate attributeName="r" dur="0.75s" repeatCount="indefinite" values="1.5;3;1.5"/></circle>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="svg-spinners:3-dots-scale-middle" /></template>
