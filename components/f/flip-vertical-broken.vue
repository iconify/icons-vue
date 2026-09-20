<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wvcj-vi3u.css';
import '../../css/a/a0ljpns4v.css';
import '../../css/k/kyzqyvbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wvcj-vi3u"/><path class="a0ljpns4v"/><path class="kyzqyvbjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flip-vertical-broken" /></template>
