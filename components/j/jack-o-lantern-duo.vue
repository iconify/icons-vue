<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mjw8hcbkc.css';
import '../../css/k/knhos3f_x.css';
import '../../css/p/pwsazko7z.css';
import '../../css/j/jv3lt9s1r.css';
import '../../css/c/cb1l5hrxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mjw8hcbkc"/><path class="knhos3f_x wm-s"/><path class="pwsazko7z wm-s"/><path class="jv3lt9s1r"/><path class="cb1l5hrxt wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:jack-o-lantern-duo" /></template>
