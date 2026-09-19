<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcfdmshpr.css';
import '../../css/y/yon6j8aod.css';
import '../../css/e/e6ldbg92l.css';
import '../../css/a/a2nsj8b2m.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--badged clr-i-outline-path-1--badged zcfdmshpr"/><path class="clr-i-outline--badged clr-i-outline-path-2--badged yon6j8aod"/><path class="clr-i-outline--badged clr-i-outline-path-3--badged e6ldbg92l"/><path class="a2nsj8b2m clr-i-outline--badged clr-i-outline-path-4--badged"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-5--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:data-cluster-outline-badged" /></template>
