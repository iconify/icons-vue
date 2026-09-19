<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2uxm_bsm.css';
import '../../css/u/uw3524s4i.css';
import '../../css/c/cnjev3bcp.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="b2uxm_bsm clr-i-outline--badged clr-i-outline-path-1--badged"/><path class="clr-i-outline--badged clr-i-outline-path-2--badged uw3524s4i"/><path class="clr-i-outline--badged clr-i-outline-path-3--badged cnjev3bcp"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-4--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:download-cloud-outline-badged" /></template>
