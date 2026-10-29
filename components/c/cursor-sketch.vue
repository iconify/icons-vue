<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hdh_7z44n.css';
import '../../css/b/b0-fhem7h.css';
import '../../css/v/v81nbqbbf.css';
import '../../css/v/v0j5nabxd.css';
import '../../css/h/hg_ketbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hdh_7z44n"/><path class="b0-fhem7h wm-k"/><path class="v81nbqbbf wm-a"/><path class="v0j5nabxd wm-k"/><path class="hg_ketbuy wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cursor-sketch" /></template>
