<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rzvi263la.css';
import '../../css/x/xujq61b3g.css';
import '../../css/a/abs9vim9l.css';
import '../../css/n/ndg34cbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rzvi263la"/><path class="wm-shadow xujq61b3g"/><path class="abs9vim9l"/><path class="ndg34cbdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-fork-engrave" /></template>
