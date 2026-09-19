<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy2utibri.css';
import '../../css/e/eajk65b4i.css';
import '../../css/i/i3i9c4uvz.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--badged clr-i-outline-path-1--badged jy2utibri"/><path class="clr-i-outline--badged clr-i-outline-path-2--badged eajk65b4i"/><path class="clr-i-outline--badged clr-i-outline-path-3--badged i3i9c4uvz"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-4--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:clock-outline-badged" /></template>
