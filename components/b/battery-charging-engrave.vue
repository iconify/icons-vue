<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/e1e5nwbtg.css';
import '../../css/j/jd-tv257l.css';
import '../../css/n/n9oyagb4p.css';
import '../../css/c/c1tkw--rs.css';
import '../../css/f/f4-qfh4mt.css';
import '../../css/i/i14ho346r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="e1e5nwbtg wm-k"/><path class="jd-tv257l wm-a"/><path class="n9oyagb4p wm-shadow"/><path class="c1tkw--rs wm-k"/><path class="f4-qfh4mt wm-a"/><path class="i14ho346r wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:battery-charging-engrave" /></template>
