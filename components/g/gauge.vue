<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/lbha9ecwq.css';
import '../../css/v/v67rwzb7l.css';
import '../../css/k/kw04ru5zn.css';
import '../../css/u/urmv84b7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="lbha9ecwq wm-shadow"/><path class="v67rwzb7l wm-shadow"/><path class="kw04ru5zn"/><path class="urmv84b7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:gauge" /></template>
