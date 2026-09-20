<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5umn5btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:for" /></template>
<style>
.n5umn5btz {
  fill: var(--svg-color--49c5ab, #49c5ab);
  d: path("M7.114 19.611v-8.964C7.114 6.425 10.576 3 14.84 3h.633a1.41 1.41 0 0 1 1.414 1.404c0 .771-.633 1.167-1.414 1.167h-.854c-2.597 0-4.932 2.315-4.932 4.886v.771h5.858a1.317 1.317 0 0 1 1.342 1.286c0 .71-.602 1.286-1.342 1.286H9.686v5.811C9.686 20.383 9.17 21 8.4 21s-1.286-.617-1.286-1.389");
}

</style>
