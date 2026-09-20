<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuxnc_b9h.css';
import '../../css/q/qj5twlbig.css';
import '../../css/i/ih7l-db9h.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/w/wm-01wyyk.css';
import '../../css/j/jnwzt6pjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="iuxnc_b9h"/><path class="qj5twlbig"/><path class="ih7l-db9h"/><g class="brzn_0bpr"><path class="wm-01wyyk"/><path class="jnwzt6pjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:facebook" /></template>
