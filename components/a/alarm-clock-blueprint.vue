<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/u/ugxv4_b0y.css';
import '../../css/h/hmwbs5mdb.css';
import '../../css/q/qhj6u7bmm.css';
import '../../css/j/jk7ggdcef.css';
import '../../css/j/jj7r4xgjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ugxv4_b0y wm-deco"/><path class="hmwbs5mdb wm-deco"/><path class="qhj6u7bmm wm-deco"/><path class="jk7ggdcef wm-k"/><path class="jj7r4xgjd wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:alarm-clock-blueprint" /></template>
