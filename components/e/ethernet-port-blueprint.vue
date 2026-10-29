<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/b/bpsdnccop.css';
import '../../css/g/g2xclxbug.css';
import '../../css/s/soc03pbkp.css';
import '../../css/f/f3tg6ebbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="bpsdnccop wm-deco"/><path class="g2xclxbug wm-deco"/><path class="soc03pbkp wm-k"/><path class="f3tg6ebbt wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ethernet-port-blueprint" /></template>
