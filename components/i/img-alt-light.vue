<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/j/jwum6hb4u.css';
import '../../css/b/bakchowuc.css';
import '../../css/y/y_fwr5blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><circle class="jwum6hb4u"/><path class="bakchowuc"/><path class="y_fwr5blk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:img-alt-light" /></template>
