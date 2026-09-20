<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5xdmn.css';
import '../../css/h/h445vw.css';
import '../../css/z/zxndow.css';
import '../../css/l/l6j71m.css';
import '../../css/q/qrxbwy.css';
import '../../css/b/botfzx.css';
import '../../css/b/bpk4qx.css';
import '../../css/s/so-from-62.css';
import '../../css/f/fade-to-1.css';
import '../../css/d/d-tnsd9f.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGVZjSodvI"><path class="c5xdmn h445vw zxndow"/><path class="c5xdmn l6j71m zxndow"/><path class="qrxbwy"/></mask></defs><path mask="url(#SVGVZjSodvI)" class="botfzx"/><path class="bpk4qx c5xdmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:folder-minus" /></template>
