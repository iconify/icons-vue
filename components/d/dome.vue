<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/a/asf7d5wcf.css';
import '../../css/o/o6wf_jbpf.css';
import '../../css/e/evm9jdbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="asf7d5wcf"/><path class="o6wf_jbpf"/><path class="evm9jdbvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dome" /></template>
