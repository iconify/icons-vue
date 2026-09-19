<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/k83jpvbjp.css';
import '../../css/x/x5rt7xbfv.css';
import '../../css/p/p9j8izb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="k83jpvbjp"/><path class="x5rt7xbfv"/><path class="p9j8izb5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:id" /></template>
