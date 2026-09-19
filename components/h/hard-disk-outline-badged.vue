<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swnh3d4fc.css';
import '../../css/t/t1v5m3rvb.css';
import '../../css/a/axgx3zgbe.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--badged clr-i-outline-path-1--badged swnh3d4fc"/><path class="clr-i-outline--badged clr-i-outline-path-2--badged t1v5m3rvb"/><path class="axgx3zgbe clr-i-outline--badged clr-i-outline-path-3--badged"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-4--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:hard-disk-outline-badged" /></template>
