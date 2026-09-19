<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b45v4c7ra.css';
import '../../css/i/inewx5b5l.css';
import '../../css/i/iu5_1fbyz.css';
import '../../css/m/m5eds2f1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b45v4c7ra"/><circle class="inewx5b5l"/><circle class="iu5_1fbyz"/><circle class="m5eds2f1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:chat" /></template>
