<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/z/z832h1bns.css';
import '../../css/g/gwy3bbbxn.css';
import '../../css/x/xzjbldrua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco z832h1bns"/><path class="gwy3bbbxn wm-k"/><path class="wm-a xzjbldrua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ice-cream-blueprint" /></template>
