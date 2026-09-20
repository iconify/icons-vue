<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/txlw-y26h.css';
import '../../css/b/bbdy775sr.css';
import '../../css/l/lvbvjwfmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="txlw-y26h"/><path clip-rule="evenodd" class="bbdy775sr"/><path class="lvbvjwfmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:crosshairs-off-filled" /></template>
