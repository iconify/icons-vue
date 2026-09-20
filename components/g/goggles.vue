<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_5xpwxqd.css';
import '../../css/g/gp87-kkrs.css';
import '../../css/t/t4kztubjt.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/p/pgn6ubbtq.css';
import '../../css/a/ao6x-sbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="i_5xpwxqd"/><path class="gp87-kkrs"/><path class="t4kztubjt"/><g class="jn8qy4bru"><path class="pgn6ubbtq"/><path class="ao6x-sbqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:goggles" /></template>
