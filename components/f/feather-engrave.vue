<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b9msuwbwv.css';
import '../../css/w/w8tee1byy.css';
import '../../css/g/ggspghb0w.css';
import '../../css/m/mnalv31ip.css';
import '../../css/u/ulw-1mb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b9msuwbwv wm-k"/><path class="w8tee1byy wm-a"/><path class="ggspghb0w wm-shadow"/><path class="mnalv31ip wm-k"/><path class="ulw-1mb-v wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:feather-engrave" /></template>
