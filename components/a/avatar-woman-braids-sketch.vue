<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fgdsbjaos.css';
import '../../css/v/vj3c051re.css';
import '../../css/l/lb5ghwnjs.css';
import '../../css/s/s3hfz9bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fgdsbjaos wm-k"/><path class="vj3c051re wm-a"/><path class="lb5ghwnjs wm-k"/><path class="s3hfz9bmt wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-woman-braids-sketch" /></template>
