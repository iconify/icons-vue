<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lnc4jbg4z.css';
import '../../css/o/ofwm1kdcx.css';
import '../../css/e/en291ygfx.css';
import '../../css/m/m_b26hb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lnc4jbg4z wm-k"/><path class="ofwm1kdcx wm-a"/><path class="en291ygfx wm-k"/><path class="m_b26hb0h wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-woman-curly-sketch" /></template>
