<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/r/rn-2cioxv.css';
import '../../css/m/m4unhhbun.css';
import '../../css/q/qa8-8s9mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rn-2cioxv"/><path class="m4unhhbun"/><path class="qa8-8s9mi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:email-action-add" /></template>
