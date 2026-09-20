<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/p/pj6h5w.css';
import '../../css/x/xeyb-r.css';
import '../../css/s/so-from-54.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c pj6h5w"/><path class="a0m25c xeyb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:filter-confirm" /></template>
