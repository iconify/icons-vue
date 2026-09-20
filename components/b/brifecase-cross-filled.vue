<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r857p_fnh.css';
import '../../css/g/g757y11st.css';
import '../../css/o/o4qapjxgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r857p_fnh"/><path class="g757y11st"/><path class="o4qapjxgu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:brifecase-cross-filled" /></template>
