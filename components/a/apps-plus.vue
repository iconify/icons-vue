<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/f/fd-ahacbo.css';
import '../../css/j/joa4c8oic.css';
import '../../css/e/eaxacq3vs.css';
import '../../css/f/firtg0hjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><rect class="fd-ahacbo"/><rect class="joa4c8oic"/><rect class="eaxacq3vs"/><path class="firtg0hjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:apps-plus" /></template>
