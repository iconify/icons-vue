<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b8hfadckz.css';
import '../../css/a/a05xr_gmb.css';
import '../../css/g/ggxoisrbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b8hfadckz"/><path class="a05xr_gmb"/><path class="ggxoisrbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gallery-favorite-filled" /></template>
