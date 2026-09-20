<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/wq6x-syyy.css';
import '../../css/g/gn0805nbm.css';
import '../../css/f/fo8mcj6fc.css';
import '../../css/a/a_9it9b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wq6x-syyy"/><path class="gn0805nbm"/><path class="fo8mcj6fc"/><path class="a_9it9b3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:globe-pointer" /></template>
