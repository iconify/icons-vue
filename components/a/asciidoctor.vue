<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vc_7-wbdv"/><path class="yk1is6beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:asciidoctor" /></template>
<style>
.vc_7-wbdv {
  fill: var(--svg-color--e40046, #e40046);
  d: path("M63.173 0C28.307 0 0 28.305 0 63.17v129.255c0 34.866 28.307 63.172 63.173 63.172h129.254c34.866 0 63.17-28.306 63.17-63.172V63.171C255.597 28.305 227.294 0 192.427 0z");
}

.yk1is6beq {
  fill: var(--svg-color--fff, #fff);
  d: path("M108.902 127.708h16.517a5.386 5.386 0 1 1 0 10.77H63.227a5.386 5.386 0 1 1 0-10.77h34.01l.05-.118l32.188-77.417a5.39 5.39 0 0 1 4.867-3.315a5.39 5.39 0 0 1 5.084 3.341l61.943 151.042a5.386 5.386 0 1 1-9.964 4.088L134.408 66.355zm-15.069 36.34q-.029.073-.06.144l-17.108 41.16a5.386 5.386 0 1 1-9.946-4.136l15.449-37.167H51.84a5.386 5.386 0 1 1 0-10.77h62.199a5.386 5.386 0 1 1 0 10.77z");
}

</style>
