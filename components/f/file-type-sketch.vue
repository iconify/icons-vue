<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qroi_17da"/><path class="dry3-u1ul"/><path class="oqw2qqboa"/><path class="lm1e6sb1l"/><path class="q-6xd1bvy"/><path class="o23joxr0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-sketch" /></template>
<style>
.dry3-u1ul {
  fill: var(--svg-color--ea6c00, #ea6c00);
  d: path("M7.671 12.395L16 28.567L2 12.395zm16.658 0L16 28.567l14-16.172z");
}

.lm1e6sb1l {
  fill: var(--svg-color--fdd231, #fdd231);
  d: path("m16 3.433l-7.891.827l-.438 8.135zm0 0l7.891.827l.438 8.135z");
}

.o23joxr0u {
  fill: var(--svg-color--feeeb7, #feeeb7);
  d: path("m16 3.433l-8.329 8.962h16.658z");
}

.oqw2qqboa {
  fill: var(--svg-color--fdad00, #fdad00);
  d: path("M7.671 12.395h16.658L16 28.567z");
}

.q-6xd1bvy {
  fill: var(--svg-color--fdad00, #fdad00);
  d: path("M30 12.395L23.891 4.26l.438 8.135zm-28 0L8.109 4.26l-.438 8.135z");
}

.qroi_17da {
  fill: var(--svg-color--fdb300, #fdb300);
  d: path("M8.109 4.26L16 3.433l7.891.828L30 12.4L16 28.567L2 12.4Z");
}

</style>
