<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mns1mn_3z.css';
import '../../css/g/gtj8_dbhn.css';
import '../../css/r/rfh5pfvvj.css';
import '../../css/s/sggd97rsj.css';
import '../../css/z/z5efzrmlv.css';
import '../../css/f/fe7ehzb3f.css';
import '../../css/m/msn809bjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mns1mn_3z"/><path class="gtj8_dbhn wm-k"/><path class="rfh5pfvvj wm-a"/><path class="sggd97rsj wm-s"/><path class="wm-k z5efzrmlv"/><path class="fe7ehzb3f wm-a"/><path class="msn809bjd wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:haunted-house-sketch" /></template>
