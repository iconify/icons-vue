<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnsftl__x.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/p8zgc5_5l.css';
import '../../css/v/vc3zpsb3l.css';
import '../../css/w/wwbzjkk7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary vnsftl__x"/><g class="dt0cm9dhy primary"><path class="p8zgc5_5l"/><path class="vc3zpsb3l"/><path class="wwbzjkk7o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gallery-vertical-duo" /></template>
