<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6w4h3bjm.css';
import '../../css/t/t9xuwrmnc.css';
import '../../css/z/zix8n4brm.css';
import '../../css/w/wg57-gbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l6w4h3bjm"/><path class="t9xuwrmnc"/><path class="zix8n4brm"/><path class="wg57-gbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-cooling-20" /></template>
