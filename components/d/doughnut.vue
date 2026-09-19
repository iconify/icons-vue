<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/se3d1wbjp.css';
import '../../css/z/z4qe3m8st.css';
import '../../css/t/t6etbsbmf.css';
import '../../css/g/gjg8mvbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="se3d1wbjp"/><path class="z4qe3m8st"/><path class="t6etbsbmf"/><path class="gjg8mvbrt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:doughnut" /></template>
