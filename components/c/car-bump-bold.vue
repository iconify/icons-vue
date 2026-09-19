<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gtx8h5bep.css';
import '../../css/b/bt4ruzd5g.css';
import '../../css/u/uji1jfbhw.css';
import '../../css/u/uynpux9kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="gtx8h5bep"/><path clip-rule="evenodd" class="bt4ruzd5g"/><path clip-rule="evenodd" class="uji1jfbhw"/><path class="uynpux9kt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:car-bump-bold" /></template>
