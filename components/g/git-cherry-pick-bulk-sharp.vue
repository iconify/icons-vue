<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rkt11rrcb"/><path class="b7poj3bab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-cherry-pick-bulk-sharp" /></template>
<style>
.b7poj3bab {
  d: path("M11.473 5.024a5.95 5.95 0 0 1 1.861-1.589A5.5 5.5 0 0 1 16 2.75c1.994 0 3.738 1.055 4.832 2.695a1 1 0 0 1-.125 1.262c-.319.32-.677.599-1.05.854c-.588.399-1.215.738-1.871 1.01c.588.837 1.06 1.749 1.404 2.712A13.7 13.7 0 0 1 20 16a1 1 0 0 1-2 0a11.7 11.7 0 0 0-.69-4.033c-.4-1.101-.982-2.138-1.774-3.005c-.692-.107-1.36-.381-1.983-.693a9.4 9.4 0 0 1-1.924-1.251c-1.626.16-2.927 1.357-3.797 2.662a10.7 10.7 0 0 0-1.341 2.93A12 12 0 0 0 6 16a1 1 0 0 1-2 0c0-1.338.193-2.67.572-3.953c.683-2.329 2.027-4.681 4.103-6.027c.842-.545 1.796-.906 2.798-.996");
}

.cuyn6tgcc {
  fill: currentColor;
}

.rkt11rrcb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.168 5.445c2.396-3.593 7.268-3.593 9.664 0a1 1 0 0 1-.125 1.262c-.319.32-.677.599-1.05.854c-.748.51-1.583.945-2.448 1.22C16.82 8.905 16.411 9 16 9s-.82-.095-1.209-.219c-.865-.275-1.7-.71-2.448-1.22a7 7 0 0 1-1.05-.854a1 1 0 0 1-.125-1.262M2 18a3 3 0 1 1 6 0a3 3 0 0 1-6 0m14 0a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
