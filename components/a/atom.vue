<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/s/s-ayi5bku.css';
import '../../css/r/rxawnrbyo.css';
import '../../css/a/auzjo7sxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="s-ayi5bku"/><path class="rxawnrbyo"/><path class="auzjo7sxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:atom" /></template>
