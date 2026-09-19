<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h8c55jjuz.css';
import '../../css/b/bx91jnigp.css';
import '../../css/m/m75sr8b7y.css';
import '../../css/v/v5wqwnbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="h8c55jjuz"/><path class="bx91jnigp"/><path class="m75sr8b7y"/><path class="v5wqwnbzp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:disc" /></template>
