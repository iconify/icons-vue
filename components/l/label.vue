<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="nuh731t5n"/><path class="d_3w8sa7p"/><path class="bjbc1obqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:label" /></template>
<style>
.bjbc1obqu {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M8.507 10.501a1 1 0 1 1-1.415-1.414L15.577.602a1 1 0 1 1 1.415 1.414z");
}

.d_3w8sa7p {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M9.952 7.772a3.66 3.66 0 0 0-5.179 0a3.662 3.662 0 1 0 5.18 5.18a3.664 3.664 0 0 0-.001-5.18m-1.53 3.65a1.499 1.499 0 1 1-2.119-2.12a1.499 1.499 0 0 1 2.119 2.12");
}

.nuh731t5n {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M32.017 20.181L17.345 5.746C16.687 5.087 15.823 5 14.96 5H4.883C3.029 5 2 6.029 2 7.883v10.082c0 .861.089 1.723.746 2.38L17.3 35.017a3.287 3.287 0 0 0 4.688 0l10.059-10.088c1.31-1.312 1.28-3.438-.03-4.748m-23.596-8.76a1.497 1.497 0 1 1-2.118-2.117a1.497 1.497 0 0 1 2.118 2.117");
}

</style>
