<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/y/yi9eumbcn.css';
import '../../css/m/m4unhhbun.css';
import '../../css/q/q0slogedd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yi9eumbcn"/><path class="m4unhhbun"/><path class="q0slogedd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:email-action-subtract" /></template>
