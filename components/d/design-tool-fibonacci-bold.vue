<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr5y6mbwg.css';
import '../../css/x/x6bcvoimv.css';
import '../../css/a/a49kqqbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr5y6mbwg"/><path class="x6bcvoimv"/><path class="a49kqqbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:design-tool-fibonacci-bold" /></template>
