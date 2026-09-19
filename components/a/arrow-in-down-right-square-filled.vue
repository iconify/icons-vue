<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opmr5m07o.css';
import '../../css/c/c5qcubb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opmr5m07o"/><path class="c5qcubb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-down-right-square-filled" /></template>
