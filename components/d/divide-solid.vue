<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqa3tkb1n.css';
import '../../css/m/mw7smgb6y.css';
import '../../css/p/pbtl3b4-t.css';
import '../../css/n/nxucm-4mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="sqa3tkb1n"><path class="mw7smgb6y"/><path class="pbtl3b4-t"/><path class="nxucm-4mi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:divide-solid" /></template>
