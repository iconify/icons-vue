<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/r/rkcgcxhua.css';
import '../../css/e/ei3k_tb3o.css';
import '../../css/t/tlhsqgbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rkcgcxhua"/><path class="ei3k_tb3o"/><path class="tlhsqgbia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-yen" /></template>
