<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="k16doe2do"/><path class="cv0i67brj"/><path class="vify63jys"/><circle class="b1fkj4-at"/><circle class="g2rewcach"/><circle transform="rotate(-80.781 21.232 30.514)" class="ecs20pfcu"/><circle transform="rotate(-80.781 15.107 32.548)" class="p1-r7rbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:face-vomiting" /></template>
<style>
.b1fkj4-at {
  cx: 15.875px;
  cy: 23.228px;
  r: 1.235px;
  fill: var(--svg-color--5d8f3f, #5d8f3f);
}

.cv0i67brj {
  fill: var(--svg-color--65471b, #65471b);
  d: path("M18 27.136c3.335 0 5.547.388 8.284.92c.625.12 1.841 0 1.841-1.841c0-3.682-4.23-8.284-10.125-8.284S7.875 22.533 7.875 26.215c0 1.841 1.216 1.962 1.841 1.841c2.736-.532 4.949-.92 8.284-.92M6.668 18.888a.944.944 0 0 1-.567-1.7c.135-.101 2.787-2.061 6.475-2.77c-2.338-1.172-4.932-1.197-4.965-1.197a.944.944 0 0 1 .002-1.889c.209 0 5.149.036 8.223 3.11a.945.945 0 0 1-.667 1.612c-4.357 0-7.898 2.618-7.933 2.644a.94.94 0 0 1-.568.19m22.664 0a.94.94 0 0 1-.564-.187c-.036-.027-3.6-2.645-7.935-2.645a.942.942 0 0 1-.667-1.612c3.075-3.075 8.015-3.11 8.223-3.11a.944.944 0 0 1 .002 1.889c-.034 0-2.629.025-4.966 1.197c3.688.708 6.34 2.668 6.475 2.77a.944.944 0 0 1-.568 1.698");
}

.ecs20pfcu {
  cx: 21.232px;
  cy: 30.515px;
  r: 1.235px;
  fill: var(--svg-color--5d8f3f, #5d8f3f);
}

.g2rewcach {
  cx: 20.698px;
  cy: 25.64px;
  r: 1.235px;
  fill: var(--svg-color--5d8f3f, #5d8f3f);
}

.k16doe2do {
  fill: var(--svg-color--ffcb4c, #ffcb4c);
  d: path("M35 17c0 9.389-7.611 17-17 17S1 26.389 1 17S8.612 0 18 0s17 7.612 17 17");
}

.p1-r7rbng {
  cx: 15.107px;
  cy: 32.548px;
  r: 1.765px;
  fill: var(--svg-color--5d8f3f, #5d8f3f);
}

.vify63jys {
  fill: var(--svg-color--77af57, #77af57);
  d: path("M25.712 32.287v-7.101c0-2.593-3.889-5.185-7.778-5.185s-7.778 2.593-7.778 5.185v7.101c-4.403.349-7.359.985-7.359 1.713c0 1.105 6.777 2 15.137 2s15.137-.895 15.137-2c0-.728-2.956-1.364-7.359-1.713");
}

</style>
