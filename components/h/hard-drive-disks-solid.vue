<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu_w_rb3z.css';
import '../../css/m/ml18l_bpc.css';
import '../../css/n/n3k6jv7dq.css';
import '../../css/s/s-u6_uyuf.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 fu_w_rb3z"/><path class="clr-i-solid clr-i-solid-path-2 ml18l_bpc"/><path class="clr-i-solid clr-i-solid-path-3 n3k6jv7dq"/><path class="clr-i-solid clr-i-solid-path-4 s-u6_uyuf"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:hard-drive-disks-solid" /></template>
