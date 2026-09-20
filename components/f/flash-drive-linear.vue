<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/ewk9ygb9b.css';
import '../../css/f/fyr67fbfm.css';
import '../../css/l/l-y11jebw.css';
import '../../css/b/baa-5bbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ewk9ygb9b"/><path class="fyr67fbfm"/><path class="ewk9ygb9b"/><path class="l-y11jebw"/><path class="baa-5bbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flash-drive-linear" /></template>
