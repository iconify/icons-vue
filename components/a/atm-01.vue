<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/q/qbbfvybck.css';
import '../../css/x/x9fzlq6gx.css';
import '../../css/f/f68r9abrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qbbfvybck"/><path class="x9fzlq6gx"/><path class="f68r9abrn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:atm-01" /></template>
