<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/x/xg1a86kbb.css';
import '../../css/k/korc1hs3g.css';
import '../../css/c/ct8ahg6rh.css';
import '../../css/r/rzkeqkbxd.css';
import '../../css/t/tcjvbpb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco xg1a86kbb"/><path class="korc1hs3g wm-deco"/><path class="ct8ahg6rh wm-deco"/><path class="rzkeqkbxd wm-k"/><path class="tcjvbpb5r wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gamepad-blueprint" /></template>
