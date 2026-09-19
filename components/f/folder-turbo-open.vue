<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/laymhdblb.css';
import '../../css/i/i3yjklbnq.css';
import '../../css/w/ww1uvxbxt.css';
import '../../css/w/wzup-8xfj.css';
import '../../css/j/jfemo-btz.css';
import '../../css/p/p0fj_zv_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ft5dv1b6b"><path class="laymhdblb"/><circle class="i3yjklbnq"/><path class="ww1uvxbxt"/><path class="wzup-8xfj"/><path class="jfemo-btz"/><path class="p0fj_zv_l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-turbo-open" /></template>
