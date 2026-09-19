<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wyuor8b1i.css';
import '../../css/k/klm28w1do.css';
import '../../css/e/eioo6acwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wyuor8b1i"/><path class="klm28w1do"/><path class="eioo6acwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:cg" /></template>
