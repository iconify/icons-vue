<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gza2rb70b.css';
import '../../css/h/h7y3db64d.css';
import '../../css/x/xgwypdh-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gza2rb70b"/><path class="h7y3db64d"/><path class="xgwypdh-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cart-add-duotone" /></template>
