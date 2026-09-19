<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr92u0wkn.css';
import '../../css/l/lcmv8kbxm.css';
import '../../css/a/aa88hnfrh.css';
import '../../css/c/c9aij2b2f.css';
import '../../css/d/dcztsobwm.css';
import '../../css/g/giefambiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jr92u0wkn"/><path class="lcmv8kbxm"/><path class="aa88hnfrh"/><path class="c9aij2b2f"/><path class="dcztsobwm"/><path class="giefambiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:lockwithinkpen" /></template>
