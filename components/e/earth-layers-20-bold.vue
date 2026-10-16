<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obb-habqc.css';
import '../../css/p/pb3usgw0j.css';
import '../../css/q/qaena785d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="obb-habqc"/><path class="pb3usgw0j"/><path class="qaena785d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:earth-layers-20-bold" /></template>
