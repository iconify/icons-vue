<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":283};
const content = `<path class="sngn7uo2o"/><path class="uc734xbhu"/><path class="x8658ib6g"/><path class="uqfo-lapb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-play-icon" /></template>
<style>
.sngn7uo2o {
  fill: var(--svg-color--ea4335, #ea4335);
  d: path("M119.553 134.916L1.06 259.061a32.14 32.14 0 0 0 47.062 19.071l133.327-75.934z");
}

.uc734xbhu {
  fill: var(--svg-color--fbbc04, #fbbc04);
  d: path("M239.37 113.814L181.715 80.79l-64.898 56.95l65.162 64.28l57.216-32.67a31.345 31.345 0 0 0 0-55.537z");
}

.uqfo-lapb {
  fill: var(--svg-color--34a853, #34a853);
  d: path("m120.436 141.274l61.278-60.483L48.564 4.503A32.85 32.85 0 0 0 32.051 0C17.644-.028 4.978 9.534 1.06 23.399z");
}

.x8658ib6g {
  fill: var(--svg-color--4285f4, #4285f4);
  d: path("M1.06 23.487A30.6 30.6 0 0 0 0 31.61v219.327a32.3 32.3 0 0 0 1.06 8.124l122.555-120.966z");
}

</style>
