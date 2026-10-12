<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wsm29rb0c.css';
import '../../css/i/im-u2lvxf.css';
import '../../css/e/eala76xrb.css';
import '../../css/v/vmh-g7inv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wsm29rb0c"/><path class="im-u2lvxf"/><path class="eala76xrb"/><path class="vmh-g7inv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:globe-lock-duotone" /></template>
