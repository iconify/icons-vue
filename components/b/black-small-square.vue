<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="upolbljfi"/><path class="u0v3_jbsx"/><path class="hnnsnmd4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:black-small-square" /></template>
<style>
.hnnsnmd4q {
  fill: var(--svg-color--787878, #787878);
  d: path("M52.03 41.283c0-1.057-.704-1.409-5.106-1.233c-3.698.176-5.459.529-6.515 1.937c-1.057 1.41-1.41 4.05-1.41 7.397c0 2.289 0 4.402 1.233 4.402c1.585 0 1.585-3.698 2.994-5.811c2.465-4.227 8.804-5.283 8.804-6.692");
}

.u0v3_jbsx {
  fill: var(--svg-color--424242, #424242);
  d: path("M41.113 36h37.681a5.11 5.11 0 0 1 5.106 5.107v37.685a5.11 5.11 0 0 1-5.106 5.107H41.113a5.11 5.11 0 0 1-5.106-5.107V41.283c-.141-2.782 2.007-5.142 4.789-5.283z");
}

.upolbljfi {
  fill: var(--svg-color--575757, #575757);
  d: path("M41.113 36h45.78A5.11 5.11 0 0 1 92 41.107v45.786A5.11 5.11 0 0 1 86.894 92H41.113a5.11 5.11 0 0 1-5.106-5.107v-45.61c-.141-2.782 2.007-5.142 4.789-5.283z");
}

</style>
