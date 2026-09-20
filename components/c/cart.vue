<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/j/jtzqtmbpa.css';
import '../../css/x/xv2mki75f.css';
import '../../css/x/x2vknkufc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="jtzqtmbpa"/><circle class="xv2mki75f"/><path class="x2vknkufc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:cart" /></template>
