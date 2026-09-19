<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw8yjoqzh.css';
import '../../css/e/e5ia2_b7c.css';
import '../../css/s/sg34wcv_c.css';
import '../../css/b/bbcnl32jx.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 dw8yjoqzh"/><rect class="clr-i-solid clr-i-solid-path-2 e5ia2_b7c"/><rect class="clr-i-solid clr-i-solid-path-3 sg34wcv_c"/><rect class="bbcnl32jx clr-i-solid clr-i-solid-path-4"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:flow-chart-solid" /></template>
