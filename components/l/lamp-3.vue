<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3xtuk_0z.css';
import '../../css/f/f6tqcpbyl.css';
import '../../css/b/buv-ombri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="l3xtuk_0z"><path class="f6tqcpbyl"/><path class="buv-ombri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:lamp-3" /></template>
