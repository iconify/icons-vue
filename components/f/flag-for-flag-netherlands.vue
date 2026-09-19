<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="kuzq5lbpv"/><path class="ec63smi6v"/><path class="fr2105bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-netherlands" /></template>
<style>
.ec63smi6v {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("M32 62c13.1 0 24.2-8.3 28.3-20H3.7C7.8 53.7 18.9 62 32 62");
}

.fr2105bnj {
  fill: var(--svg-color--fff, #fff);
  d: path("M3.7 22C2.6 25.1 2 28.5 2 32s.6 6.9 1.7 10h56.6c1.1-3.1 1.7-6.5 1.7-10s-.6-6.9-1.7-10z");
}

.kuzq5lbpv {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 2C18.9 2 7.8 10.3 3.7 22h56.6C56.2 10.3 45.1 2 32 2");
}

</style>
