<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/s/sfvl1ubyd.css';
import '../../css/b/bnfk6lbbp.css';
import '../../css/r/rbzq4bjzv.css';
import '../../css/x/x4e1woonj.css';
import '../../css/i/ip7h18bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="sfvl1ubyd wm-deco"/><path class="bnfk6lbbp wm-deco"/><path class="rbzq4bjzv wm-deco"/><path class="wm-k x4e1woonj"/><path class="ip7h18bdm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bauble-blueprint" /></template>
