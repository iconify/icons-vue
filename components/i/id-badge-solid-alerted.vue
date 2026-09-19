<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9iy3go4i.css';
import '../../css/d/dxl-uqb-c.css';
import '../../css/e/ezxbjlbqv.css';
import '../../css/d/dxqmhhbtw.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--alerted clr-i-solid-path-1--alerted q9iy3go4i"/><circle class="clr-i-solid--alerted clr-i-solid-path-2--alerted dxl-uqb-c"/><path class="clr-i-solid--alerted clr-i-solid-path-3--alerted ezxbjlbqv"/><path class="clr-i-solid--alerted clr-i-solid-path-4--alerted dxqmhhbtw"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-5--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:id-badge-solid-alerted" /></template>
