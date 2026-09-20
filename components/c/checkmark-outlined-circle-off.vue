<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ir1bwpb5n.css';
import '../../css/h/hqxv7vfui.css';
import '../../css/n/nlp5r_b7n.css';
import '../../css/z/zsuclwbnx.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ir1bwpb5n"/><path clip-rule="evenodd" class="hqxv7vfui"/><path clip-rule="evenodd" class="nlp5r_b7n"/><path class="zsuclwbnx"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:checkmark-outlined-circle-off" /></template>
