<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dcw4ccctf.css';
import '../../css/c/c7zsidbio.css';
import '../../css/a/aga97actr.css';
import '../../css/l/luym5ou8t.css';
import '../../css/r/retdkbgbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="dcw4ccctf"/><path clip-rule="evenodd" class="c7zsidbio"/><path class="aga97actr"/><path clip-rule="evenodd" class="luym5ou8t"/><path clip-rule="evenodd" class="retdkbgbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:countdown" /></template>
