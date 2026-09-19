<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="banzgttlg"/><path class="lahjdcwzw"/><path class="ps108rbcl"/><path class="xcilytfbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-djibouti" /></template>
<style>
.banzgttlg {
  fill: var(--svg-color--009e60, #009e60);
  d: path("M32.454 32.03L4.11 52.25c1.538 1.106 3.499 1.754 5.89 1.754h44c6.627 0 10-4.925 10-11v-11H32.416z");
}

.lahjdcwzw {
  fill: var(--svg-color--6ab2e7, #6ab2e7);
  d: path("M54 10H10c-2.201 0-4.04.553-5.514 1.5L32.416 32H64V21c0-6.075-3.373-11-10-11");
}

.ps108rbcl {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M32.416 32L4.486 11.5C1.513 13.407 0 16.942 0 21v22c0 3.883 1.385 7.289 4.11 9.246l28.344-20.219z");
}

.xcilytfbt {
  fill: var(--svg-color--be1e2d, #be1e2d);
  d: path("m21.06 28.357l-6.303.016l-1.95-6.379l-1.945 6.379l-6.308-.016l5.109 3.883l-1.976 6.334l5.124-3.936l5.132 3.936l-1.982-6.334z");
}

</style>
