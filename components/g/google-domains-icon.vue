<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":239};
const content = `<path class="alvbaebgj"/><path class="e442v9xbb"/><path class="rdxvcgbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-domains-icon" /></template>
<style>
.alvbaebgj {
  fill: var(--svg-color--4285f4, #4285f4);
  d: path("M247.17 0c6.333 0 10.606 6.467 8.104 12.28L166.02 225.8a21.4 21.4 0 0 1-19.633 12.877H85.39c-6.333 0-10.76-6.256-8.238-12.069l6.987-16.765l15.244-89.023l44.29-53.837l22.56-54.106C169.6 5.062 175.912 0 184.44 0z");
}

.e442v9xbb {
  fill: var(--svg-color--fbbc04, #fbbc04);
  d: path("M143.981 66.233c-15.514-15.071-36.764-24.253-60.13-24.003C37.038 42.75-.515 81.015.004 127.692c.5 45.945 37.707 82.902 83.537 83.556c.212-.577 40.999-64.597 40.999-64.597s19.44-80.38 19.44-80.418");
}

.rdxvcgbnu {
  fill: var(--svg-color--ea4335, #ea4335);
  d: path("M143.981 66.233S83.484 211.267 83.542 211.267q1.098.03 2.194 0c46.831-.52 84.365-38.765 83.845-85.461c-.25-23.367-10.028-44.425-25.6-59.573");
}

</style>
