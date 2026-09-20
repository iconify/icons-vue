<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="layer"><path class="unwrg5b1s"/><path class="fqkk5zbfj"/><path class="o62u5cblf"/><path class="v1714rytf"/><path class="txt-vxbce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-sapphire-framework-cli" /></template>
<style>
.fqkk5zbfj {
  fill: var(--svg-color--254fb9, #254fb9);
  d: path("M10.788 22.622L16 29.007l5.206-6.376l.007-4.51l-10.426 3.833z");
}

.o62u5cblf {
  fill: var(--svg-color--5280dd, #5280dd);
  d: path("m16.485 4.055l.682-.693l-1.166-1.189l-6.148 6.251V10.8l1.696-1.724l-.002-.001l-.76.774l5.214-6.386zm5.663 19.518v-1.899l-.94.957L16 29.007l-.483-.59l-.451.457l.934.95zm-.94-.943l.006-.008l-1.32 1.342z");
}

.txt-vxbce {
  fill: var(--svg-color--254fb9, #254fb9);
  d: path("M10.788 9.849L16 3.463l5.213 6.386v.757l-10.426 5.628z");
}

.unwrg5b1s {
  fill: var(--svg-color--95e8e8, #95e8e8);
  d: path("m10.788 9.85l-.935.95v12.772l5.214 5.302l.451-.458v-.001l-4.73-5.793zm10.426 0v12.774l-.007.009l.941-.957V8.424l-4.98-5.064l-.682.694z");
}

.v1714rytf {
  fill: var(--svg-color--729ef4, #729ef4);
  d: path("M21.214 18.12v-7.514l-10.426 5.628v5.72z");
}

</style>
