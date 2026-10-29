<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/p/p3zfr5b_b.css';
import '../../css/v/vze4wuf6n.css';
import '../../css/h/hig_4pcic.css';
import '../../css/r/rqrk7ccgu.css';
import '../../css/j/jwr308vyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="p3zfr5b_b wm-deco"/><path class="vze4wuf6n wm-deco"/><path class="hig_4pcic wm-k"/><path class="rqrk7ccgu wm-a"/><path class="jwr308vyi wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:images-blueprint" /></template>
