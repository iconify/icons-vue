<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pyidsligx.css';
import '../../css/a/a0atj0kuc.css';
import '../../css/d/dwr3y3bmi.css';
import '../../css/b/b_d68_bhp.css';
import '../../css/a/ar0r6f66r.css';
import '../../css/b/bos0j4biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pyidsligx wm-k"/><path class="a0atj0kuc wm-a"/><path class="dwr3y3bmi wm-shadow"/><path class="b_d68_bhp wm-k"/><path class="ar0r6f66r wm-a"/><path class="bos0j4biy wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:landmark-engrave" /></template>
