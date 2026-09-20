<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtsnveitd.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vt533fbwo.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/n/nteqkgdxx.css';
import '../../css/a/aisxi3qis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGabXJgcxD" class="vtsnveitd"/></defs><g class="cuyn6tgcc"><path clip-rule="evenodd" class="vt533fbwo"/><use href="#SVGabXJgcxD" clip-rule="evenodd" class="d2kvgvbvc"/><path class="nteqkgdxx"/><use href="#SVGabXJgcxD" clip-rule="evenodd" class="d2kvgvbvc"/><path class="aisxi3qis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:lightning-duotone" /></template>
