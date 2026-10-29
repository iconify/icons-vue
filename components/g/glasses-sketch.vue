<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tm4gzzgqh.css';
import '../../css/b/bbdvx11fu.css';
import '../../css/c/cdn7lcb3n.css';
import '../../css/b/b1d8a7blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tm4gzzgqh wm-shine"/><path class="bbdvx11fu wm-k"/><path class="cdn7lcb3n wm-k"/><path class="b1d8a7blo wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:glasses-sketch" /></template>
