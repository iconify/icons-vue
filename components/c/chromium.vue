<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz-_5oksg.css';
import '../../css/g/gt5tzr3ur.css';
import '../../css/r/rvfx8xmjp.css';
import '../../css/j/j0wz0zsox.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/j/jj7lh75iy.css';
import '../../css/i/ix7nckcdq.css';
import '../../css/u/usozxnbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="sz-_5oksg"/><path clip-rule="evenodd" class="gt5tzr3ur"/><path clip-rule="evenodd" class="rvfx8xmjp"/><circle class="j0wz0zsox"/><g class="brzn_0bpr"><circle class="jj7lh75iy"/><path class="ix7nckcdq"/><circle class="usozxnbrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:chromium" /></template>
