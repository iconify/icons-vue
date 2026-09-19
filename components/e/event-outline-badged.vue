<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nje91rp-p.css';
import '../../css/b/b54bhv41g.css';
import '../../css/v/vojd3wb9c.css';
import '../../css/x/x7ii9pxzv.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--badged clr-i-outline-path-1--badged nje91rp-p"/><path class="b54bhv41g clr-i-outline--badged clr-i-outline-path-2--badged"/><path class="clr-i-outline--badged clr-i-outline-path-3--badged vojd3wb9c"/><path class="clr-i-outline--badged clr-i-outline-path-4--badged x7ii9pxzv"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-5--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:event-outline-badged" /></template>
