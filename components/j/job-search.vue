<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/eh311nzoy.css';
import '../../css/f/fjk1_yb_p.css';
import '../../css/i/iqlx6k-bs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="eh311nzoy"/><path class="fjk1_yb_p"/><path class="iqlx6k-bs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:job-search" /></template>
