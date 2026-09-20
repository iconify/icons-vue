<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uzmao7bka"/><path class="b4z9wvbwt"/><path class="o1rn68bgt"/><path class="o87fpccpm"/><path class="q0nfr1oko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-gcp" /></template>
<style>
.b4z9wvbwt {
  fill: var(--svg-color--ea4335, #ea4335);
  d: path("M22.229 17.061h.732l2.086-2.086l.1-.886A9.377 9.377 0 0 0 9.9 18.664a1.14 1.14 0 0 1 .732-.043l4.172-.689s.213-.351.322-.329a5.206 5.206 0 0 1 7.123-.542Z");
}

.o1rn68bgt {
  fill: var(--svg-color--4285f4, #4285f4);
  d: path("M28.019 18.664a9.4 9.4 0 0 0-2.833-4.564l-2.928 2.928a5.2 5.2 0 0 1 1.911 4.128v.52a2.606 2.606 0 0 1 0 5.212h-5.212l-.52.527v3.126l.52.519h5.212a6.778 6.778 0 0 0 3.85-12.393Z");
}

.o87fpccpm {
  fill: var(--svg-color--34a853, #34a853);
  d: path("M13.738 31.028h5.212v-4.172h-5.212a2.6 2.6 0 0 1-1.076-.235l-.732.227l-2.1 2.086l-.183.732a6.74 6.74 0 0 0 4.091 1.362");
}

.q0nfr1oko {
  fill: var(--svg-color--fbbc05, #fbbc05);
  d: path("M13.738 17.493a6.778 6.778 0 0 0-4.092 12.151l3.023-3.023a2.606 2.606 0 1 1 3.448-3.447l3.023-3.024a6.77 6.77 0 0 0-5.402-2.657");
}

.uzmao7bka {
  fill: var(--svg-color--bf55bf, #bf55bf);
  d: path("M27.9 6h-9.8l-2 4H5v17h25V6Zm.1 4h-7.8l1-2H28Z");
}

</style>
