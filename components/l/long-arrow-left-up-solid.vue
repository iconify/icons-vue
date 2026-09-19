<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqa3tkb1n.css';
import '../../css/t/t77t6gbxy.css';
import '../../css/g/ga300c6qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="sqa3tkb1n"><path class="t77t6gbxy"/><path class="ga300c6qn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:long-arrow-left-up-solid" /></template>
