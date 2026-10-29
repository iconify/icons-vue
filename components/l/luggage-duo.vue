<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hw5l17qef.css';
import '../../css/k/kgvwdybzv.css';
import '../../css/p/pr4hfob0i.css';
import '../../css/t/t1hpgfxns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hw5l17qef"/><path class="kgvwdybzv wm-a"/><path class="pr4hfob0i"/><path class="t1hpgfxns wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:luggage-duo" /></template>
