<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkaxou.css';
import '../../css/t/t5pxry.css';
import '../../css/z/zxndow.css';
import '../../css/l/li54_l.css';
import '../../css/y/y4wbml.css';
import '../../css/i/icc8up.css';
import '../../css/b/botfzx.css';
import '../../css/m/mxeyef.css';
import '../../css/s/s8e22g.css';
import '../../css/k/kzf8bf.css';
import '../../css/s/so-from-64.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';
import '../../css/f/fade-to-1.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGUMqceprV"><path class="lkaxou t5pxry zxndow"/><path class="li54_l t5pxry y4wbml zxndow"/><path class="icc8up"/></mask></defs><path mask="url(#SVGUMqceprV)" class="botfzx"/><path class="mxeyef s8e22g t5pxry y4wbml"/><path class="kzf8bf s8e22g t5pxry y4wbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:briefcase-plus-filled" /></template>
