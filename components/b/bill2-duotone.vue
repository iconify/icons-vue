<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ibhpxzb1a.css';
import '../../css/l/li59jccuh.css';
import '../../css/o/ozff5bcpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ibhpxzb1a"/><path class="li59jccuh"/><path clip-rule="evenodd" class="ozff5bcpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bill2-duotone" /></template>
