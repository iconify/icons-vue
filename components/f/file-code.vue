<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/t/tuk6cqr0l.css';
import '../../css/j/js_oh4-0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="tuk6cqr0l"/><path class="js_oh4-0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:file-code" /></template>
