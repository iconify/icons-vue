<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/v801p--8a.css';
import '../../css/b/bscjyvifb.css';
import '../../css/o/o-0hp-bqv.css';
import '../../css/w/wqunvdbhs.css';
import '../../css/f/f6ehwtaid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="bullseye-outline"><g class="Vector cuyn6tgcc"><path clip-rule="evenodd" class="v801p--8a"/><path clip-rule="evenodd" class="bscjyvifb"/><path clip-rule="evenodd" class="o-0hp-bqv"/><path class="wqunvdbhs"/><path clip-rule="evenodd" class="f6ehwtaid"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:bullseye-outline" /></template>
