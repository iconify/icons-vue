<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox-nzf.css';
import '../../css/u/u6fdno.css';
import '../../css/y/ydovum.css';
import '../../css/l/lx2oxu.css';
import '../../css/g/gq-uqf.css';
import '../../css/d/djbuks.css';
import '../../css/t/th60ya.css';
import '../../css/s/so-from-56.css';
import '../../css/f/fade-to-1.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox-nzf"/><circle class="u6fdno ydovum"/><circle class="lx2oxu ydovum"/><circle class="gq-uqf ydovum"/><circle class="djbuks ydovum"/><circle class="th60ya ydovum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:cookie" /></template>
