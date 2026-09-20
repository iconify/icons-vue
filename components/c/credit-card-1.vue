<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rodx-bbgi.css';
import '../../css/u/usszxechu.css';
import '../../css/y/yxybwwqbg.css';
import '../../css/u/u6wus0bjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rodx-bbgi"/><path class="usszxechu"/><path class="yxybwwqbg"/><path class="u6wus0bjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:credit-card-1" /></template>
