<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lqwztrbou.css';
import '../../css/s/sh1k6zb2q.css';
import '../../css/p/pc7mq_i4b.css';
import '../../css/e/ejv5f_b2g.css';
import '../../css/g/gwoq6gb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="lqwztrbou"/><path class="sh1k6zb2q"/><path class="pc7mq_i4b"/><path class="ejv5f_b2g"/><path class="gwoq6gb2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:giraffe" /></template>
