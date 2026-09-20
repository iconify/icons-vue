<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/u/ujco1sofn.css';
import '../../css/t/tnu8150qt.css';
import '../../css/h/hg6wvbcts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ujco1sofn"/><path class="tnu8150qt"/><path class="hg6wvbcts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:city-hall-flat" /></template>
