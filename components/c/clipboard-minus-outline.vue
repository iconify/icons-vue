<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/agobzcc3y.css';
import '../../css/h/h4-tcib6f.css';
import '../../css/g/g_cdedu9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="agobzcc3y"/><path class="h4-tcib6f"/><path class="g_cdedu9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-minus-outline" /></template>
