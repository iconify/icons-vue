<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5rcylbor.css';
import '../../css/b/b1py72uxf.css';
import '../../css/v/v9wygdb8u.css';
import '../../css/e/ev4yihl-v.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 l5rcylbor"/><circle class="b1py72uxf clr-i-outline clr-i-outline-path-2"/><circle class="clr-i-outline clr-i-outline-path-3 v9wygdb8u"/><path class="clr-i-outline clr-i-outline-path-4 ev4yihl-v"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:happy-face-line" /></template>
