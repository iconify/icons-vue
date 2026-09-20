<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjo_ierie.css';
import '../../css/n/n4cmayroc.css';
import '../../css/z/z8szqbbhz.css';
import '../../css/d/dbv864swk.css';
import '../../css/i/i26g8db7o.css';
import '../../css/i/ibwo_2fsy.css';
import '../../css/t/tgv7n4j2u.css';
import '../../css/b/bldcl9bcs.css';
import '../../css/m/m0rr3ob_d.css';
import '../../css/t/tpfi6eauu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="vjo_ierie"/><path class="n4cmayroc"/><path class="z8szqbbhz"/><path class="dbv864swk"/><circle class="i26g8db7o"/><path class="ibwo_2fsy"/><path class="tgv7n4j2u"/><circle class="bldcl9bcs"/><path class="m0rr3ob_d"/><path class="tpfi6eauu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:bear" /></template>
