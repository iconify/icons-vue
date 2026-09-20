<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv52cm.css';
import '../../css/t/t5pxry.css';
import '../../css/z/zxndow.css';
import '../../css/w/wa90th.css';
import '../../css/y/y4wbml.css';
import '../../css/c/ccv_gr.css';
import '../../css/o/oxx-om.css';
import '../../css/b/botfzx.css';
import '../../css/g/gd_4-q.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-50.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGv75uO00M"><path class="sv52cm t5pxry zxndow"/><path class="t5pxry wa90th y4wbml zxndow"/><path class="ccv_gr oxx-om t5pxry y4wbml"/></mask></defs><path mask="url(#SVGv75uO00M)" class="botfzx"/><path class="ccv_gr gd_4-q t5pxry y4wbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:laptop-off-twotone" /></template>
