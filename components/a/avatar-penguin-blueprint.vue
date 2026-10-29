<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/n/nlz8ktj-e.css';
import '../../css/m/mbsk0fc1j.css';
import '../../css/e/ei333ac_w.css';
import '../../css/e/ew-k0jbco.css';
import '../../css/k/k1xf4_bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="nlz8ktj-e wm-deco"/><path class="mbsk0fc1j wm-deco"/><path class="ei333ac_w wm-deco"/><path class="ew-k0jbco wm-k"/><path class="k1xf4_bso wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-penguin-blueprint" /></template>
