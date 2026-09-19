<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/j850wac-i.css';
import '../../css/u/u_haqyhvf.css';
import '../../css/z/zrt4urc1f.css';
import '../../css/z/zsrvp_b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="j850wac-i"/><path class="u_haqyhvf"/><circle class="zrt4urc1f"/><circle class="zsrvp_b7g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:engineering-vehicle" /></template>
