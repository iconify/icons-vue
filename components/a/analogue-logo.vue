<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-5kdesz.css';
import '../../css/m/mq8ul-5qi.css';
import '../../css/t/t4-ohwb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path clip-rule="evenodd" class="mq8ul-5qi"/><path class="t4-ohwb_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:analogue-logo" /></template>
