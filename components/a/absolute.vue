<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xqmepvbqz.css';
import '../../css/j/j36ww4b-u.css';
import '../../css/c/cn4bvt4si.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xqmepvbqz"/><path class="j36ww4b-u"/><path class="cn4bvt4si"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:absolute" /></template>
