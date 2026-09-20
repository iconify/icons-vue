<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o-qo2ebal.css';
import '../../css/h/hu8pocc6e.css';
import '../../css/n/n0digdb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o-qo2ebal"/><path class="hu8pocc6e"/><path class="n0digdb4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:brush" /></template>
