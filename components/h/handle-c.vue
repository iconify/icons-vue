<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/h/hrq90hfel.css';
import '../../css/m/mepo-8bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="wwvp95byt"><circle class="hrq90hfel"/><path class="mepo-8bga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:handle-c" /></template>
