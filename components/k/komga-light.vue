<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6w7gxzsp.css';
import '../../css/m/mcgtvq47v.css';
import '../../css/g/gjl24ib1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u6w7gxzsp"/><path class="mcgtvq47v"/><path class="gjl24ib1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:komga-light" /></template>
