<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="r5hh8mbef"/><path class="lywutp9gw"/><path class="kahu35bqb"/><path class="lus8k155t"/><path class="z81zmvbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-cape-verde" /></template>
<style>
.kahu35bqb {
  fill: var(--svg-color--cf2027, #cf2027);
  d: path("M0 21v3h36v-3z");
}

.lus8k155t {
  fill: var(--svg-color--003893, #003893);
  d: path("M4 31h28a4 4 0 0 0 4-4v-1H0v1a4 4 0 0 0 4 4");
}

.lywutp9gw {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 19h36v2H0zm0 5h36v2H0z");
}

.r5hh8mbef {
  fill: var(--svg-color--003893, #003893);
  d: path("M32 5H4a4 4 0 0 0-4 4v10h36V9a4 4 0 0 0-4-4");
}

.z81zmvbyg {
  fill: var(--svg-color--f7d116, #f7d116);
  d: path("m14.347 15.903l.764-.555h-.944l-.292-.898l-.292.898h-.944l.764.555l-.292.899l.764-.555l.764.555zm6.182 4.492l.764-.555h-.944l-.292-.899l-.292.899h-.945l.765.555l-.292.898l.764-.555l.764.555zm-12.364 0l.765-.555h-.945l-.292-.899l-.292.899h-.944l.764.555l-.292.898l.764-.555l.764.555zm0 4.017l.765-.555h-.945l-.292-.898l-.292.898h-.944l.764.555l-.292.898l.764-.555l.764.555zm12.364 0l.764-.555h-.944l-.292-.898l-.292.898h-.945l.765.555l-.292.898l.764-.555l.764.555zm-6.362 3.936l-.292-.898l-.292.898h-.944l.764.555l-.292.899l.764-.555l.764.555l-.292-.899l.764-.555zm4.001-.686l.764-.555h-.945l-.291-.898l-.292.898h-.945l.764.555l-.292.898l.765-.555l.764.555zm0-10.504l.764-.555h-.945l-.291-.898l-.292.898h-.945l.764.555l-.292.898l.765-.555l.764.555zM9.582 27.662l-.764-.555h.945l.291-.898l.292.898h.945l-.764.555l.292.898l-.765-.555l-.764.555zm0-10.504l-.764-.555h.945l.291-.898l.292.898h.945l-.764.555l.292.898l-.765-.555l-.764.555z");
}

</style>
