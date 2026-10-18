<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="layer"><path class="ri219wbru"/><path class="blvr96bbd"/><path class="kzrvdkncl"/><path class="m1ch5im5x"/><path class="z2h-c8avw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-sapphire-framework-cli" /></template>
<style>
.blvr96bbd {
  fill: var(--svg-color--254fb9, #254fb9);
  d: path("m10.787 22.623l5.214 6.387l5.205-6.376l.007-4.511l-10.425 3.833z");
}

.kzrvdkncl {
  fill: var(--svg-color--5280dd, #5280dd);
  d: path("m16.485 4.055l.682-.694L16 2.171L9.855 8.426V10.8l1.694-1.725l-.76.773L16 3.463zm5.662 19.52v-1.898l-.94.958L16 29.01l-.484-.591l-.45.458l.934.95zm-.94-.943l.006-.009l-1.32 1.343z");
}

.m1ch5im5x {
  fill: var(--svg-color--729ef4, #729ef4);
  d: path("M21.214 18.123v-7.516l-10.427 5.629v5.72z");
}

.ri219wbru {
  fill: var(--svg-color--95e8e8, #95e8e8);
  d: path("m10.787 9.85l-.933.951v12.772l5.212 5.303l.451-.458l-4.729-5.795zm10.425 0v12.776l-.007.01l.941-.958V8.425l-4.978-5.066l-.682.695z");
}

.z2h-c8avw {
  fill: var(--svg-color--254fb9, #254fb9);
  d: path("m10.787 9.85l5.214-6.387l5.212 6.386v.758l-10.425 5.629z");
}

</style>
