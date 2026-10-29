<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/x6yjo2boq.css';
import '../../css/v/v9xe62b0c.css';
import '../../css/b/bq6kxj32x.css';
import '../../css/f/fm32n2byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k x6yjo2boq"/><path class="v9xe62b0c wm-shadow"/><path class="bq6kxj32x wm-k"/><path class="fm32n2byj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:fish-engrave" /></template>
