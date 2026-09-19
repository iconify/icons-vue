<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfdi2lb9a.css';
import '../../css/u/ullydzbrg.css';
import '../../css/v/v1i4-0kax.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--alerted clr-i-outline-path-1--alerted nfdi2lb9a"/><path class="clr-i-outline--alerted clr-i-outline-path-2--alerted ullydzbrg"/><path class="clr-i-outline--alerted clr-i-outline-path-3--alerted v1i4-0kax"/><path class="clr-i-alert clr-i-outline--alerted clr-i-outline-path-4--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:display-outline-alerted" /></template>
