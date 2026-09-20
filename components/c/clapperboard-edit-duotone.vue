<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lvwbaqb1f.css';
import '../../css/g/g1jyq1e1a.css';
import '../../css/k/kfalkfbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lvwbaqb1f"/><path clip-rule="evenodd" class="g1jyq1e1a"/><path class="kfalkfbzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:clapperboard-edit-duotone" /></template>
