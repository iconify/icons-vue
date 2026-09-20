<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1724o.css';
import '../../css/a/a0m25c.css';
import '../../css/d/ddx_6x.css';
import '../../css/d/d-uxzh.css';
import '../../css/i/idmydr.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';
import '../../css/s/so-from-20.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1724o"/><path class="a0m25c ddx_6x"/><path class="a0m25c d-uxzh"/><path class="a0m25c idmydr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:edit-twotone" /></template>
