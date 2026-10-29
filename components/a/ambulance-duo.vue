<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/ajado-bbb.css';
import '../../css/k/k02fzkb_b.css';
import '../../css/r/r7lp1bc0o.css';
import '../../css/c/c2osk-a-j.css';
import '../../css/k/kloo_bcmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ajado-bbb"/><path class="k02fzkb_b wm-a"/><path class="r7lp1bc0o wm-a"/><path class="c2osk-a-j"/><path class="kloo_bcmp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ambulance-duo" /></template>
