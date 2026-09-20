<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or51mp33s.css';
import '../../css/l/ljtl2bbyd.css';
import '../../css/m/mhsun10on.css';
import '../../css/o/oai19b_2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="or51mp33s"/><path class="ljtl2bbyd"/><path class="mhsun10on"/><path class="oai19b_2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:asp-net-core" /></template>
