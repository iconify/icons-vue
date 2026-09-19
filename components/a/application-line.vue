<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufi4okb0l.css';
import '../../css/k/k0z7a6b-h.css';
import '../../css/t/tcbb08bkr.css';
import '../../css/e/e8fs2zb1o.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 ufi4okb0l"/><path class="clr-i-outline clr-i-outline-path-2 k0z7a6b-h"/><path class="clr-i-outline clr-i-outline-path-3 tcbb08bkr"/><path class="clr-i-outline clr-i-outline-path-4 e8fs2zb1o"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:application-line" /></template>
