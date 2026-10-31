<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u7a-skb_d.css';
import '../../css/i/i1l12gbrg.css';
import '../../css/t/t16a2vbbm.css';
import '../../css/f/fk7l6bzdb.css';
import '../../css/f/f22davn1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u7a-skb_d wm-k"/><path class="i1l12gbrg wm-shine"/><path class="t16a2vbbm wm-shine"/><path class="fk7l6bzdb wm-shine"/><path class="f22davn1p wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:folder-open" /></template>
