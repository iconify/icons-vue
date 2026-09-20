<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mk2kad5se.css';
import '../../css/t/tqd73obgx.css';
import '../../css/m/mzb3cwb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mk2kad5se"/><path class="tqd73obgx"/><path class="mzb3cwb-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:error-triangle" /></template>
