<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/io40x634q.css';
import '../../css/a/a4usxjbwv.css';
import '../../css/g/g6ebdibnz.css';
import '../../css/k/k2k6wrbli.css';
import '../../css/u/uk4liwe1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="io40x634q wm-k"/><path class="a4usxjbwv wm-a"/><path class="g6ebdibnz wm-shadow"/><path class="k2k6wrbli wm-k"/><path class="uk4liwe1r wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:contactless-engrave" /></template>
