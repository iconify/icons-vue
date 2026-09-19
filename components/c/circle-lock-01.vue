<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/r9ixvp21u.css';
import '../../css/p/po3o6yboy.css';
import '../../css/a/an13f2b6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="r9ixvp21u"/><path class="po3o6yboy"/><path class="an13f2b6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:circle-lock-01" /></template>
