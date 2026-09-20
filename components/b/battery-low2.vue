<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fk1cwvbyo.css';
import '../../css/j/j246-ubvw.css';
import '../../css/h/huq9i0-2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fk1cwvbyo"/><path clip-rule="evenodd" class="j246-ubvw"/><path class="huq9i0-2s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:battery-low2" /></template>
