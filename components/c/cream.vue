<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9-4ocb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cream" /></template>
<style>
.y9-4ocb9h {
  fill: var(--svg-color--69e2db, #69e2db);
  d: path("m14.217 12.67l5.009 4.98a.95.95 0 0 1-.101 1.424a9.06 9.06 0 0 1-13.26-2.318A8.976 8.976 0 0 1 9.62 3.89a9.08 9.08 0 0 1 9.54 1.058a.94.94 0 0 1 .061 1.396l-5.009 4.986a.95.95 0 0 0-.281.687c0 .13.028.259.079.377a1 1 0 0 0 .208.31z");
}

</style>
