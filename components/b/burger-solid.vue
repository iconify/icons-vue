<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qs96w4bbe.css';
import '../../css/e/eh36yibok.css';
import '../../css/o/ohgkzfgww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qs96w4bbe"/><path class="eh36yibok"/><path class="ohgkzfgww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:burger-solid" /></template>
