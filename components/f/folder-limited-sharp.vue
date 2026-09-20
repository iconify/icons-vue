<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e62cmpsqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-limited-sharp" /></template>
<style>
.e62cmpsqg {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2H21v12zm11.402-3.906q.983-.982.983-2.402t-.983-2.401q-.983-.983-2.402-.983t-2.402.983t-.983 2.401t.983 2.402q.983.983 2.402.983t2.402-.983m-3.821-4.448q.313-.221.665-.337t.754-.117q1.05 0 1.775.725t.725 1.775q0 .402-.116.754q-.117.352-.338.666zM12 15.192q-1.05 0-1.775-.725T9.5 12.692q0-.401.116-.753q.117-.352.338-.666l3.465 3.466q-.313.22-.665.337q-.352.116-.754.116");
}

</style>
