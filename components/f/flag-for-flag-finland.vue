<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="pmeol1b8p"/><path class="sd9ob5qik"/><path class="ehiw23vsj"/><path class="ib2y5sbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-finland" /></template>
<style>
.ehiw23vsj {
  fill: var(--svg-color--edecec, #edecec);
  d: path("M32 31H18V21h18v6a4 4 0 0 1-4 4m-21 0H4a4 4 0 0 1-4-4v-6h11z");
}

.ib2y5sbss {
  fill: var(--svg-color--003580, #003580);
  d: path("M18 5h-7v10H0v6h11v10h7V21h18v-6H18z");
}

.pmeol1b8p {
  fill: var(--svg-color--edecec, #edecec);
  d: path("M32 5H18v10h18V9a4 4 0 0 0-4-4");
}

.sd9ob5qik {
  fill: var(--svg-color--eee, #eee);
  d: path("M11 5H4a4 4 0 0 0-4 4v6h11z");
}

</style>
