<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="rifdf8-wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flash-28-regular" /></template>
<style>
.rifdf8-wc {
  fill: currentColor;
  d: path("M8.406 2.852A1.33 1.33 0 0 1 9.65 2h8.516c.927 0 1.57.922 1.252 1.792L17.324 9.5h4.837c1.178 0 1.777 1.416.957 2.262L9.784 25.503c-1.14 1.175-3.106.117-2.753-1.482l1.66-7.521H5.917a1.917 1.917 0 0 1-1.787-2.61zm1.358.648L5.528 14.433a.417.417 0 0 0 .389.567h3.708a.75.75 0 0 1 .732.912l-1.861 8.433c-.01.047-.002.069.004.08a.14.14 0 0 0 .059.057a.14.14 0 0 0 .08.018c.012-.002.035-.007.069-.041L21.768 11H16.25a.75.75 0 0 1-.704-1.008l2.38-6.492z");
}

</style>
