<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5xdmn.css';
import '../../css/h/hmd6rr.css';
import '../../css/z/zxndow.css';
import '../../css/p/pfsmgv.css';
import '../../css/z/zahr3u.css';
import '../../css/o/oxx-om.css';
import '../../css/u/ux4wzr.css';
import '../../css/b/botfzx.css';
import '../../css/g/gd_4-q.css';
import '../../css/s/so-from-70.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGjlYOSbpY"><path class="c5xdmn hmd6rr zxndow"/><path class="c5xdmn pfsmgv zxndow"/><path class="c5xdmn zahr3u zxndow"/><path class="c5xdmn oxx-om ux4wzr"/></mask></defs><path mask="url(#SVGjlYOSbpY)" class="botfzx"/><path class="c5xdmn gd_4-q ux4wzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:chat-alert-off" /></template>
