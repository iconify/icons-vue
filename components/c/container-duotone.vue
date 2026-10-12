<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qps5svx2l.css';
import '../../css/d/d7tmwc-kq.css';
import '../../css/l/lbpgzetic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qps5svx2l"/><path class="d7tmwc-kq"/><path class="lbpgzetic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:container-duotone" /></template>
