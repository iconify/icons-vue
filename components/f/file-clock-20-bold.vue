<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-ljzcb_h.css';
import '../../css/z/z2szi_geo.css';
import '../../css/d/d1xy-t7vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s-ljzcb_h"/><path class="z2szi_geo"/><path class="d1xy-t7vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-clock-20-bold" /></template>
