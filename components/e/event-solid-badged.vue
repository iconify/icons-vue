<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b54bhv41g.css';
import '../../css/u/u60v_2ieg.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="b54bhv41g clr-i-solid--badged clr-i-solid-path-1--badged"/><path class="clr-i-solid--badged clr-i-solid-path-2--badged u60v_2ieg"/><circle class="clr-i-badge clr-i-solid--badged clr-i-solid-path-3--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:event-solid-badged" /></template>
