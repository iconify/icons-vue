<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/b/b74rkzv8a.css';
import '../../css/v/vy7ah-75i.css';
import '../../css/m/mz2x21b7z.css';
import '../../css/l/l-wis9b-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="b74rkzv8a wm-deco"/><path class="vy7ah-75i wm-k"/><path class="mz2x21b7z wm-a"/><path class="l-wis9b-x wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:eye-off-blueprint" /></template>
