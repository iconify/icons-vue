<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/ste35xvlg.css';
import '../../css/h/hlb_npbvv.css';
import '../../css/w/wpwd_2bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ste35xvlg"/><path class="hlb_npbvv"/><path class="wpwd_2bno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hammer-duotone" /></template>
