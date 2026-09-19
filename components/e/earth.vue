<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/banyp_byo.css';
import '../../css/l/lgi2hbckz.css';
import '../../css/j/jhlnkxs0e.css';
import '../../css/m/mstzhuakk.css';
import '../../css/i/ixb2frykk.css';
import '../../css/u/ueb4e2brx.css';
import '../../css/j/jyip9nbmh.css';
import '../../css/v/vtg06xuau.css';
import '../../css/o/oqul2lg-c.css';
import '../../css/o/o1u_i577p.css';
import '../../css/u/u4s6ccbhz.css';
import '../../css/v/vco61q_by.css';
import '../../css/b/bu_qf0qdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<circle class="banyp_byo"/><circle class="lgi2hbckz"/><path class="jhlnkxs0e"/><circle class="mstzhuakk"/><circle class="ixb2frykk"/><circle class="ueb4e2brx"/><circle class="jyip9nbmh"/><circle class="vtg06xuau"/><circle class="oqul2lg-c"/><circle class="o1u_i577p"/><path class="u4s6ccbhz"/><path class="vco61q_by"/><path class="bu_qf0qdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:earth" /></template>
