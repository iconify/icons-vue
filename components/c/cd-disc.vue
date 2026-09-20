<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/m_dn-5bgg.css';
import '../../css/i/i06p4_b4q.css';
import '../../css/p/pxt9w6gls.css';
import '../../css/g/gflirmbze.css';
import '../../css/x/xjpsjs4db.css';
import '../../css/v/vo_bpkbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="m_dn-5bgg"/><path class="i06p4_b4q"/><path class="pxt9w6gls"/><path class="gflirmbze"/><path class="xjpsjs4db"/><path class="vo_bpkbcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:cd-disc" /></template>
