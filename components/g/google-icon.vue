<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":262};
const content = `<path class="kt9hewhoc"/><path class="pyvm3-bxv"/><path class="g_pe54euh"/><path class="vvtx1cbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-icon" /></template>
<style>
.g_pe54euh {
  fill: var(--svg-color--fbbc05, #fbbc05);
  d: path("M56.281 156.37c-2.756-8.123-4.351-16.827-4.351-25.82c0-8.994 1.595-17.697 4.206-25.82l-.073-1.73L15.26 71.312l-1.335.635C5.077 89.644 0 109.517 0 130.55s5.077 40.905 13.925 58.602z");
}

.kt9hewhoc {
  fill: var(--svg-color--4285f4, #4285f4);
  d: path("M255.878 133.451c0-10.734-.871-18.567-2.756-26.69H130.55v48.448h71.947c-1.45 12.04-9.283 30.172-26.69 42.356l-.244 1.622l38.755 30.023l2.685.268c24.659-22.774 38.875-56.282 38.875-96.027");
}

.pyvm3-bxv {
  fill: var(--svg-color--34a853, #34a853);
  d: path("M130.55 261.1c35.248 0 64.839-11.605 86.453-31.622l-41.196-31.913c-11.024 7.688-25.82 13.055-45.257 13.055c-34.523 0-63.824-22.773-74.269-54.25l-1.531.13l-40.298 31.187l-.527 1.465C35.393 231.798 79.49 261.1 130.55 261.1");
}

.vvtx1cbub {
  fill: var(--svg-color--eb4335, #eb4335);
  d: path("M130.55 50.479c24.514 0 41.05 10.589 50.479 19.438l36.844-35.974C195.245 12.91 165.798 0 130.55 0C79.49 0 35.393 29.301 13.925 71.947l42.211 32.783c10.59-31.477 39.891-54.251 74.414-54.251");
}

</style>
