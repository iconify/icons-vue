<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bnndz9hbn.css';
import '../../css/r/r70z4z73s.css';
import '../../css/d/dz3e1ibvs.css';
import '../../css/s/sv8__t8-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bnndz9hbn wm-k"/><path class="r70z4z73s wm-shadow"/><path class="dz3e1ibvs wm-k"/><path class="sv8__t8-c wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lightbulb-engrave" /></template>
