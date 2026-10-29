<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lh4ximboh.css';
import '../../css/l/lk9w6fb3r.css';
import '../../css/j/jzx63eb_y.css';
import '../../css/x/xw85vjb7b.css';
import '../../css/z/zbgyb8bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lh4ximboh wm-k"/><path class="lk9w6fb3r wm-a"/><path class="jzx63eb_y wm-shadow"/><path class="wm-k xw85vjb7b"/><path class="wm-a zbgyb8bwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-moon-engrave" /></template>
