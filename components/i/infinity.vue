<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbk-atbuk.css';
import '../../css/r/rye0tjbbq.css';
import '../../css/m/mli6aj6lh.css';
import '../../css/j/jm3ds0t3h.css';
import '../../css/r/r083qn64g.css';
import '../../css/j/j-6d7-blj.css';
import '../../css/i/irh6vxbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbk-atbuk wm-shadow"/><path class="rye0tjbbq"/><path class="mli6aj6lh"/><path class="jm3ds0t3h"/><path class="r083qn64g"/><path class="j-6d7-blj wm-shine"/><path class="irh6vxbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-plush:infinity" /></template>
