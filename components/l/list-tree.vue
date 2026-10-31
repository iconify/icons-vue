<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/c/c4vdbmbtb.css';
import '../../css/x/xs5smy_1q.css';
import '../../css/n/nq3eg7a1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="c4vdbmbtb wm-shadow"/><path class="wm-shadow xs5smy_1q"/><path class="nq3eg7a1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:list-tree" /></template>
