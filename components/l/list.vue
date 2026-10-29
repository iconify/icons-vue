<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cklkuz5cm.css';
import '../../css/u/u04mw40zl.css';
import '../../css/x/xh2h04buo.css';
import '../../css/j/jknzmzbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cklkuz5cm wm-a"/><path class="u04mw40zl wm-a"/><path class="wm-a xh2h04buo"/><path class="jknzmzbge wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:list" /></template>
