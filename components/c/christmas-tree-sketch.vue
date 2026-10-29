<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jixpp3-6j.css';
import '../../css/j/jp156pb3t.css';
import '../../css/a/ausc7d0hd.css';
import '../../css/z/ztkh4mbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jixpp3-6j wm-k"/><path class="jp156pb3t wm-a"/><path class="ausc7d0hd wm-k"/><path class="wm-a ztkh4mbjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:christmas-tree-sketch" /></template>
