<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mj6oigypz.css';
import '../../css/g/g930zob6l.css';
import '../../css/x/xmjt7ob1m.css';
import '../../css/x/xzg0hfbtu.css';
import '../../css/s/sagbwcczu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mj6oigypz"/><path class="g930zob6l wm-k"/><path class="wm-s xmjt7ob1m"/><path class="wm-k xzg0hfbtu"/><path class="sagbwcczu wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:house-plus-sketch" /></template>
