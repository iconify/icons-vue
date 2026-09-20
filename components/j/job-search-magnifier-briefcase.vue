<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/e/epuchabnl.css';
import '../../css/h/h22qwyaft.css';
import '../../css/u/uxo8fdb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="epuchabnl"/><path class="h22qwyaft"/><path class="uxo8fdb3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:job-search-magnifier-briefcase" /></template>
