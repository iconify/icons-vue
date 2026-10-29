<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/c/cmj9i73hd.css';
import '../../css/n/nge5cfbll.css';
import '../../css/o/or3gi1b5y.css';
import '../../css/k/kk0fjtbcv.css';
import '../../css/w/wkhticbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="cmj9i73hd wm-deco"/><path class="nge5cfbll wm-deco"/><path class="or3gi1b5y wm-k"/><path class="kk0fjtbcv wm-a"/><path class="wkhticbiw wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:layout-list-blueprint" /></template>
