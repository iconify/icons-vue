<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3xwghbbt.css';
import '../../css/e/e9kh_hcnc.css';
import '../../css/e/e5k4d038e.css';
import '../../css/m/mnqxknb5h.css';
import '../../css/m/mi4ifbrrd.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 g3xwghbbt"/><path class="clr-i-outline clr-i-outline-path-2 e9kh_hcnc"/><path class="clr-i-outline clr-i-outline-path-3 e5k4d038e"/><path class="clr-i-outline clr-i-outline-path-4 mnqxknb5h"/><path class="clr-i-outline clr-i-outline-path-5 mi4ifbrrd"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:archive-line" /></template>
