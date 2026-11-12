<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvrll1__l.css';
import '../../css/t/tr0pmhbxp.css';
import '../../css/d/d_fb3dbwg.css';
import '../../css/i/i9wuo-33s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qvrll1__l"/><path class="tr0pmhbxp"/><path class="d_fb3dbwg"/><path class="i9wuo-33s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:excalidash-light" /></template>
