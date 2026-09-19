<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoo-kwbnt.css';
import '../../css/v/v5pb8-byn.css';
import '../../css/g/gk8hcxbvc.css';
import '../../css/t/t_4k26iyn.css';
import '../../css/h/hvn2tnezz.css';
import '../../css/t/ttnt112wp.css';
import '../../css/w/w7z_vzaig.css';
import '../../css/g/gr8lgwbjh.css';
import '../../css/a/a9c-qkbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="yoo-kwbnt"/><path clip-rule="evenodd" class="v5pb8-byn"/><path clip-rule="evenodd" class="gk8hcxbvc"/><path clip-rule="evenodd" class="t_4k26iyn"/><path clip-rule="evenodd" class="hvn2tnezz"/><path clip-rule="evenodd" class="ttnt112wp"/><path clip-rule="evenodd" class="w7z_vzaig"/><path clip-rule="evenodd" class="gr8lgwbjh"/><path clip-rule="evenodd" class="a9c-qkbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:book" /></template>
