<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xguvk2b9u.css';
import '../../css/u/u4i3hsbah.css';
import '../../css/q/qe66mdbpf.css';
import '../../css/n/np5c3ubxn.css';
import '../../css/r/rm3s91bss.css';
import '../../css/k/kbu3fm_0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-shadow xguvk2b9u"/><path class="u4i3hsbah wm-k"/><path class="qe66mdbpf wm-k"/><path class="np5c3ubxn wm-k"/><path class="rm3s91bss wm-k"/><path class="kbu3fm_0o wm-shine"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:drag-handle" /></template>
