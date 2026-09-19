<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr_-zobgp.css';
import '../../css/s/switkv-0r.css';
import '../../css/s/s7rdiavyv.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--alerted clr-i-outline-path-1--alerted xr_-zobgp"/><path class="clr-i-alert clr-i-outline--alerted clr-i-outline-path-2--alerted switkv-0r"/><path class="clr-i-outline--alerted clr-i-outline-path-3--alerted s7rdiavyv"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:battery-outline-alerted" /></template>
