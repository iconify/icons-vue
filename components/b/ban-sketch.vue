<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bksvuqoix.css';
import '../../css/w/wn6sq5bdr.css';
import '../../css/z/zoi-i9f3r.css';
import '../../css/s/s_8u5ojaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bksvuqoix"/><path class="wm-k wn6sq5bdr"/><path class="wm-k zoi-i9f3r"/><path class="s_8u5ojaz wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ban-sketch" /></template>
