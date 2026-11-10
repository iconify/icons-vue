<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/f/fcpug8qfn.css';
import '../../css/i/i4gf_wb7q.css';
import '../../css/m/m_hxi5hql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="fcpug8qfn"/><path class="i4gf_wb7q"/><path class="m_hxi5hql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:coins" /></template>
