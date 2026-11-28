<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmblh-wku.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bckwe4qia.css';
import '../../css/e/eg485t5kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmblh-wku secondary"/><g class="dt0cm9dhy primary"><path class="bckwe4qia"/><path class="eg485t5kb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:key-round-duo" /></template>
