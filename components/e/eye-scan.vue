<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/ko5lcq0hn.css';
import '../../css/a/actkwtdjy.css';
import '../../css/g/ga_jcgb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ko5lcq0hn"/><path clip-rule="evenodd" class="actkwtdjy"/><path clip-rule="evenodd" class="ga_jcgb2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:eye-scan" /></template>
