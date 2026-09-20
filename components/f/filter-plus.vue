<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/p/pj6h5w.css';
import '../../css/i/i1bv_o.css';
import '../../css/h/hy9wxw.css';
import '../../css/s/so-from-54.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c pj6h5w"/><path class="a0m25c i1bv_o"/><path class="a0m25c hy9wxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:filter-plus" /></template>
