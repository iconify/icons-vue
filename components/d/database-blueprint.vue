<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/v/vzl1p1bpj.css';
import '../../css/a/ayhs6pbko.css';
import '../../css/g/gdk50x15v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="vzl1p1bpj wm-deco"/><path class="ayhs6pbko wm-deco"/><path class="gdk50x15v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:database-blueprint" /></template>
