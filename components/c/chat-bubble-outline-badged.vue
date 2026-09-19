<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_m1urv6e.css';
import '../../css/t/t4i08l8qa.css';
import '../../css/z/zb-bw0bat.css';
import '../../css/k/kgvzshqph.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--badged clr-i-outline-path-1--badged k_m1urv6e"/><path class="clr-i-outline--badged clr-i-outline-path-2--badged t4i08l8qa"/><path class="clr-i-outline--badged clr-i-outline-path-3--badged zb-bw0bat"/><path class="clr-i-outline--badged clr-i-outline-path-4--badged kgvzshqph"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-5--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:chat-bubble-outline-badged" /></template>
