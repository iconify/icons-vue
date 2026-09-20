<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuwavpbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:key-off-outline-sharp" /></template>
<style>
.cuwavpbyv {
  fill: currentColor;
  d: path("m19.827 21.248l-7.242-7.242h-1q-.57 1.35-1.81 2.172T7 17q-2.077 0-3.538-1.461T2 12q0-1.746 1.072-3.083q1.072-1.336 2.73-1.694l-3.05-3.05l.714-.708L20.535 20.54zM20.788 10l2 2l-3.21 3.171l-1.982-1.669l-.73.539l-.385-.385l1.423-1.021l1.627 1.215L21.387 12l-1-1h-6.562l-1-1zM7 16q1.275 0 2.349-.764q1.074-.765 1.467-2.115h.884l-1.342-1.342l-1.184-1.184l-1.183-1.184L6.648 8.07q-1.657.104-2.653 1.303Q3 10.572 3 12q0 1.65 1.175 2.825T7 16m-.874-3.126q-.357-.357-.357-.874t.357-.874t.874-.357t.874.357t.357.874t-.357.874t-.874.357t-.874-.357");
}

</style>
