<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u-89ex_1l.css';
import '../../css/o/o_89d8juo.css';
import '../../css/m/mqioy1r3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u-89ex_1l wm-k"/><path class="o_89d8juo wm-k"/><path class="mqioy1r3z wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:anchor-sketch" /></template>
