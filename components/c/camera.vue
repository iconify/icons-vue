<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/y/yqwp33b_f.css';
import '../../css/m/mezodq4vs.css';
import '../../css/v/vr0thfpje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="yqwp33b_f"/><rect class="mezodq4vs"/><path class="vr0thfpje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:camera" /></template>
