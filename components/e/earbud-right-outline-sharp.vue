<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ma5pqeb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:earbud-right-outline-sharp" /></template>
<style>
.ma5pqeb2b {
  fill: currentColor;
  d: path("M12.442 21v-9.327h-2.75v-1h3.75V20h2.77v-9.327H19V6H9.692V5H20v6.673h-2.788V21zm-3.48-7.327q-2.116 0-3.539-1.586T4 8.327t1.423-3.75T8.961 3h.731v10.673zm-.27-.99V3.99q-1.638.08-2.665 1.367T5 8.346t1.027 2.97q1.027 1.267 2.665 1.367m0-4.356");
}

</style>
