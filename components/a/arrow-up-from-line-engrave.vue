<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l2699lbin.css';
import '../../css/b/bew9icbsw.css';
import '../../css/n/ntmpc3u6d.css';
import '../../css/b/bmeezab9v.css';
import '../../css/e/eyr57ibcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l2699lbin wm-k"/><path class="bew9icbsw wm-a"/><path class="ntmpc3u6d wm-shadow"/><path class="bmeezab9v wm-a"/><path class="eyr57ibcj wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-up-from-line-engrave" /></template>
