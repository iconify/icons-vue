<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wu7n7fbvu.css';
import '../../css/a/a-p3vpbvu.css';
import '../../css/e/efj4m1bby.css';
import '../../css/w/wnh8xqb5r.css';
import '../../css/d/dd0jd4bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wu7n7fbvu"/><path class="a-p3vpbvu wm-k"/><path class="efj4m1bby wm-a"/><path class="wm-k wnh8xqb5r"/><path class="dd0jd4bgv wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cube-sketch" /></template>
