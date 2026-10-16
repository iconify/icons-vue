<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc_5blf9f.css';
import '../../css/g/gl1l9lb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lc_5blf9f"/><path class="gl1l9lb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:image-off-48" /></template>
