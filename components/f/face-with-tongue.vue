<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="urvtz7e9f"/><circle class="fbn8-kl8v"/><path class="lee246tvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:face-with-tongue" /></template>
<style>
.fbn8-kl8v {
  cx: 43.5px;
  cy: 24.5px;
  r: 5px;
  fill: currentColor;
}

.lee246tvv {
  fill: currentColor;
  d: path("M32 2C15.431 2 2 15.432 2 32s13.431 30 30 30c16.568 0 30-13.432 30-30S48.568 2 32 2m.002 58c-5.521-.004-10-4.398-10-13.156v-3.995c0-.531.113-.849.822-.849H30.5l1.502 13.789L33.5 42h7.68c.708 0 .822.317.822.849v3.995c0 8.758-4.479 13.152-10 13.156m8.486-1.856c1.647-1.895 2.881-4.573 3.328-8.203c3.394-2.907 5.187-6.981 5.187-10.94c0-.493-.392-1-1.125-1H16.125C15.392 38 15 38.507 15 39c0 3.957 1.792 8.029 5.183 10.937c.446 3.638 1.69 6.313 3.342 8.211C12.498 54.564 4.5 44.205 4.5 32C4.5 16.836 16.836 4.5 32 4.5S59.5 16.836 59.5 32c0 12.201-7.992 22.557-19.012 26.144");
}

.urvtz7e9f {
  cx: 20.5px;
  cy: 24.5px;
  r: 5px;
  fill: currentColor;
}

</style>
