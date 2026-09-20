<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgihau-wd.css';
import '../../css/s/s5od5637z.css';
import '../../css/o/olmyeubsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1039.699,"height":585.831};
const content = `<path class="zgihau-wd"/><path class="s5od5637z"/><path class="olmyeubsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:el-corte-ingles" /></template>
