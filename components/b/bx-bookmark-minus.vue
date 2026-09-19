<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxmkebcbg.css';
import '../../css/w/wfs41yb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxmkebcbg"/><path class="wfs41yb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-bookmark-minus" /></template>
