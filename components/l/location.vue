<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n6l39ob8u.css';
import '../../css/b/bsqx4bc-w.css';
import '../../css/i/i34px_bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="n6l39ob8u"/><path class="bsqx4bc-w"/><path class="i34px_bie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:location" /></template>
