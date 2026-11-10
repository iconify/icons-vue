<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/t/tm40wxbko.css';
import '../../css/p/pmzx7qbms.css';
import '../../css/x/x_71-s_ta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="tm40wxbko"/><path class="pmzx7qbms"/><path class="x_71-s_ta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:beta" /></template>
