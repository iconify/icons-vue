<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j_xmk2b5o.css';
import '../../css/a/agdjpvb3s.css';
import '../../css/a/aps5q31pr.css';
import '../../css/h/h23a8zycn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j_xmk2b5o wm-k"/><path class="agdjpvb3s wm-a"/><path class="aps5q31pr wm-k"/><path class="h23a8zycn wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-up-sketch" /></template>
