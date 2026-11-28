<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fix9ebc5t.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/th4j2yb1q.css';
import '../../css/c/cyk-_qf_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fix9ebc5t secondary"/><g class="dt0cm9dhy primary"><path class="th4j2yb1q"/><path class="cyk-_qf_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:book-open-duo" /></template>
