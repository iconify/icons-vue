<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/ky_c7b80d.css';
import '../../css/n/nlm_cm0qu.css';
import '../../css/f/f_ps57bze.css';
import '../../css/s/se_om3jvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ky_c7b80d"/><path class="nlm_cm0qu"/><path class="f_ps57bze"/><path clip-rule="evenodd" class="se_om3jvd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:code-circle-outline" /></template>
