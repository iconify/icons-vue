<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vm8ob7cuz.css';
import '../../css/v/vq51a2bep.css';
import '../../css/w/wwdkt39lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vm8ob7cuz"/><path class="vq51a2bep"/><path class="wwdkt39lk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:linux" /></template>
