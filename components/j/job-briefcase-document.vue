<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lezyyqbrb.css';
import '../../css/y/yfyu5b4ac.css';
import '../../css/r/rhuwopb-f.css';
import '../../css/s/sw0djkbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="lezyyqbrb"/><path class="yfyu5b4ac"/><path class="rhuwopb-f"/><path class="sw0djkbmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:job-briefcase-document" /></template>
