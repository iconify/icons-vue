<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c202792cm.css';
import '../../css/e/ey8oes-9q.css';
import '../../css/j/jqys2dbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c202792cm"/><path class="ey8oes-9q"/><path class="jqys2dbeu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:charity" /></template>
