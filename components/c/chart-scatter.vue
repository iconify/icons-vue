<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjqd6hdic.css';
import '../../css/o/ot4tzybry.css';
import '../../css/s/st1r0ibvj.css';
import '../../css/v/vpd3c9b3n.css';
import '../../css/i/ippd80bcd.css';
import '../../css/c/carg0zb0w.css';
import '../../css/t/tgnbyebvq.css';
import '../../css/b/bwohyzbes.css';
import '../../css/e/evmri-7fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjqd6hdic wm-shadow"/><path class="ot4tzybry wm-k"/><path class="st1r0ibvj wm-k"/><path class="vpd3c9b3n wm-k"/><path class="ippd80bcd wm-k"/><path class="carg0zb0w wm-k"/><path class="tgnbyebvq wm-shine"/><path class="bwohyzbes wm-a"/><path class="evmri-7fl wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:chart-scatter" /></template>
