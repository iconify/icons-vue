<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/arvvodb9x.css';
import '../../css/j/jfegy5qom.css';
import '../../css/u/u-utrpgcn.css';
import '../../css/b/bg9_r-b3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="arvvodb9x"/><path class="jfegy5qom wm-a"/><path class="u-utrpgcn wm-k"/><path class="bg9_r-b3k wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folder-up-sketch" /></template>
