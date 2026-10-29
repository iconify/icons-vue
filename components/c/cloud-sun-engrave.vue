<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lh4ximboh.css';
import '../../css/a/a5a7_neia.css';
import '../../css/z/za81krjzn.css';
import '../../css/x/xw85vjb7b.css';
import '../../css/r/rcz-smdjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lh4ximboh wm-k"/><path class="a5a7_neia wm-a"/><path class="wm-shadow za81krjzn"/><path class="wm-k xw85vjb7b"/><path class="rcz-smdjy wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-sun-engrave" /></template>
