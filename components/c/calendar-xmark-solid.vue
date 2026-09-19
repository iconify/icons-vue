<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqa3tkb1n.css';
import '../../css/i/i3fv60jeg.css';
import '../../css/x/xxaa87b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="sqa3tkb1n"><path class="i3fv60jeg"/><path class="xxaa87b_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:calendar-xmark-solid" /></template>
