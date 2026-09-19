<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/p/p2iw4076h.css';
import '../../css/b/bi_pd3nyo.css';
import '../../css/d/d53tfdb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p2iw4076h"/><path class="bi_pd3nyo"/><path class="d53tfdb2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cash-02" /></template>
