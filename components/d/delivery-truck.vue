<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/i/imaf3zb1o.css';
import '../../css/o/ohg80ks9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="imaf3zb1o"/><path class="ohg80ks9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:delivery-truck" /></template>
