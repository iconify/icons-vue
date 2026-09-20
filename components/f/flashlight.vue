<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wn67mnb5e.css';
import '../../css/t/t304wbb4h.css';
import '../../css/u/ubbjctbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wn67mnb5e"/><path class="t304wbb4h"/><path class="ubbjctbkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:flashlight" /></template>
