<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/oa29y7bly.css';
import '../../css/a/a1wq3abcj.css';
import '../../css/m/m_g4t8b0d.css';
import '../../css/q/qb8r96btl.css';
import '../../css/o/o54qorbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="oa29y7bly wm-k"/><path class="a1wq3abcj wm-a"/><path class="m_g4t8b0d wm-shadow"/><path class="qb8r96btl wm-k"/><path class="o54qorbnl wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-checks-engrave" /></template>
