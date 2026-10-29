<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/ttlc-na8v.css';
import '../../css/p/po6tsm3ou.css';
import '../../css/l/l2miw0nqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ttlc-na8v"/><path class="po6tsm3ou"/><path class="l2miw0nqo wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:graduation-cap" /></template>
