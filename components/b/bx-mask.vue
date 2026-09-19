<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aleoypblh.css';
import '../../css/q/qqfcp2vpb.css';
import '../../css/j/j496qmb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aleoypblh"/><ellipse class="qqfcp2vpb"/><ellipse class="j496qmb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-mask" /></template>
