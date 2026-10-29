<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/ch216303n.css';
import '../../css/v/vrog6-bvp.css';
import '../../css/x/x5alubcsr.css';
import '../../css/h/hmb0o_-2y.css';
import '../../css/b/b86buo32x.css';
import '../../css/k/ki55z6ilg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ch216303n wm-k"/><path class="vrog6-bvp wm-a"/><path class="wm-shadow x5alubcsr"/><path class="hmb0o_-2y wm-a"/><path class="b86buo32x wm-k"/><path class="ki55z6ilg wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lock-engrave" /></template>
