<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jf47y0bux.css';
import '../../css/s/sjv0-obmg.css';
import '../../css/g/g66d78b4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="jf47y0bux"/><path class="sjv0-obmg"/><path clip-rule="evenodd" class="g66d78b4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:credit-card-plus-solid" /></template>
