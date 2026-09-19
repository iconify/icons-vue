<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvwfwbb0g.css';
import '../../css/p/ptkyfbcbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvwfwbb0g"/><path class="ptkyfbcbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-group" /></template>
