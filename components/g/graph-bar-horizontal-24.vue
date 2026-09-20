<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3jd1lb0p.css';
import '../../css/u/uoxnjgbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3jd1lb0p"/><path class="uoxnjgbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:graph-bar-horizontal-24" /></template>
