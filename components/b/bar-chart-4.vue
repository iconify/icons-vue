<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wav--fbep.css';
import '../../css/p/p1jwip47c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wav--fbep"/><path clip-rule="evenodd" class="p1jwip47c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bar-chart-4" /></template>
