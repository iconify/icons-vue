<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/beq2bq-ru.css';
import '../../css/g/gitu83bla.css';
import '../../css/a/azlmfgbpz.css';
import '../../css/v/vu-t8mz1s.css';
import '../../css/i/idh12yb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="beq2bq-ru wm-k"/><path class="gitu83bla wm-shadow"/><path class="azlmfgbpz wm-k"/><path class="vu-t8mz1s wm-k"/><path class="idh12yb8z wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:house-plus-engrave" /></template>
