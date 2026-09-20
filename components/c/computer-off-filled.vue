<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuzxbl.css';
import '../../css/t/t5pxry.css';
import '../../css/y/y4wbml.css';
import '../../css/z/zxndow.css';
import '../../css/t/tcaw-r.css';
import '../../css/d/dynovx.css';
import '../../css/o/oxx-om.css';
import '../../css/b/botfzx.css';
import '../../css/g/gd_4-q.css';
import '../../css/s/so-from-8.css';
import '../../css/s/so-to-0.css';
import '../../css/f/fill-to-1.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGuzT67dfa"><path class="fuzxbl t5pxry y4wbml zxndow"/><path class="t5pxry tcaw-r zxndow"/><path class="dynovx oxx-om t5pxry y4wbml"/></mask></defs><path mask="url(#SVGuzT67dfa)" class="botfzx"/><path class="dynovx gd_4-q t5pxry y4wbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:computer-off-filled" /></template>
