<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k5utv-8st.css';
import '../../css/q/qr4ochb5c.css';
import '../../css/g/gcl_rzbbb.css';
import '../../css/c/cph2zc1da.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="k5utv-8st"/><path class="qr4ochb5c wm-s"/><path class="gcl_rzbbb"/><path class="cph2zc1da wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:eye-off-duo" /></template>
