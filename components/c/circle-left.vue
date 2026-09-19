<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzwd2419d.css';
import '../../css/q/q-i98cb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lzwd2419d"/><path class="q-i98cb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:circle-left" /></template>
