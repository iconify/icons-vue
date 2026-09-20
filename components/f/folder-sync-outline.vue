<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/z40zw9udh.css';
import '../../css/q/qn8ujjbrp.css';
import '../../css/w/w_8fmvbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z40zw9udh"/><path class="qn8ujjbrp"/><path clip-rule="evenodd" class="w_8fmvbbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-sync-outline" /></template>
