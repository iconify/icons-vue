<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m_37_ob0k.css';
import '../../css/q/qt83qvb_u.css';
import '../../css/c/ccochw3vc.css';
import '../../css/o/osa342_sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m_37_ob0k"/><path class="qt83qvb_u"/><circle class="ccochw3vc"/><rect class="osa342_sq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:camera-duotone" /></template>
