<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/s/s_8f41qkd.css';
import '../../css/r/rlvt8hb4n.css';
import '../../css/q/q1antqapf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="s_8f41qkd"/><path class="rlvt8hb4n"/><path class="q1antqapf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:file-plus" /></template>
