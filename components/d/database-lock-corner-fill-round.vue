<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9f22ccnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:database-lock-corner-fill-round" /></template>
<style>
.o9f22ccnp {
  fill: currentColor;
  d: path("M16 6v3a1 1 0 0 1-2 0v-.149c-2.712 1.537-7.288 1.537-10 0V11c0 .197.112.376.235.522c.26.307.613.527.97.705C6.34 12.794 7.743 13 9 13a1 1 0 0 1 0 2c-1.676 0-3.526-.313-5-1.149V16c0 .197.112.376.235.522c.26.307.613.527.97.705C6.34 17.794 7.743 18 9 18a1 1 0 0 1 0 2c-1.578 0-3.268-.274-4.69-.984c-.599-.3-1.166-.688-1.602-1.202C2.276 17.302 2 16.676 2 16V6c0-.676.276-1.302.708-1.814c2.465-2.913 10.119-2.913 12.584 0C15.724 4.698 16 5.324 16 6m6 12v1a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3v-1c0-1.27.803-2.405 2-2.829V15a3 3 0 1 1 6 0v.171A3 3 0 0 1 22 18m-6-3h2a1 1 0 0 0-2 0m-2 3v1a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1v-1a1 1 0 0 0-1-1h-4a1 1 0 0 0-1 1");
}

</style>
