<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g52mlw2ar.css';
import '../../css/i/ivtb9ubih.css';
import '../../css/b/b8qt8lbsk.css';
import '../../css/l/lx85cvamk.css';
import '../../css/a/a2xqgdbch.css';
import '../../css/v/vpat_6qhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="g52mlw2ar"/><path class="ivtb9ubih"/><path class="b8qt8lbsk"/><path class="lx85cvamk"/><path class="a2xqgdbch"/><path class="vpat_6qhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:hourglass-full" /></template>
