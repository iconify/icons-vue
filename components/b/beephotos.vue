<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3xdyvzhs.css';
import '../../css/m/m--ipvi-j.css';
import '../../css/g/gch5xlsgc.css';
import '../../css/b/b1__pbbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m3xdyvzhs"/><path class="m--ipvi-j"/><path class="gch5xlsgc"/><path class="b1__pbbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beephotos" /></template>
