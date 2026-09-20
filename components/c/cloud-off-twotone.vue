<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oncedd.css';
import '../../css/a/ae_viy.css';
import '../../css/c/c5xdmn.css';
import '../../css/z/zxndow.css';
import '../../css/c/cn_flp.css';
import '../../css/l/l1irms.css';
import '../../css/o/oxx-om.css';
import '../../css/b/botfzx.css';
import '../../css/g/gd_4-q.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-22.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGjDFgFeCP"><path class="oncedd"/><path class="ae_viy c5xdmn zxndow"/><path class="c5xdmn cn_flp zxndow"/><path class="c5xdmn l1irms oxx-om"/></mask></defs><path mask="url(#SVGjDFgFeCP)" class="botfzx"/><path class="c5xdmn gd_4-q l1irms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:cloud-off-twotone" /></template>
