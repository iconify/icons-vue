<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yl6qyqbtf.css';
import '../../css/w/wcn0p-kxr.css';
import '../../css/y/ytg3nrqhy.css';
import '../../css/c/c6ortbcgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yl6qyqbtf"/><path class="wcn0p-kxr"/><path class="ytg3nrqhy"/><path class="c6ortbcgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:allowances-no-smoking" /></template>
