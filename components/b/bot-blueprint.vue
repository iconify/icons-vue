<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/b/b7r660gyh.css';
import '../../css/d/d9fohpece.css';
import '../../css/x/xurpiib7h.css';
import '../../css/v/v7thhccnj.css';
import '../../css/x/xpemu4q5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="b7r660gyh wm-deco"/><path class="d9fohpece wm-deco"/><path class="wm-deco xurpiib7h"/><path class="v7thhccnj wm-k"/><path class="wm-a xpemu4q5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bot-blueprint" /></template>
