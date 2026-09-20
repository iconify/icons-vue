<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dgh7jhswh"/><g class="n1mjunbsu"><path class="eo5z8sbaz"/><path class="gcvwq2btm"/><path class="jne663b5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:gemini" /></template>
<style>
.dgh7jhswh {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.eo5z8sbaz {
  d: path("M28.999 30.5a1.5 1.5 0 0 1-.475-.077c-.02-.006-2.975-.923-10.525-.923s-10.505.917-10.535.926c-.785.253-1.631-.178-1.887-.962s.165-1.626.947-1.887c.133-.044 3.325-1.077 11.475-1.077s11.343 1.033 11.475 1.077a1.5 1.5 0 0 1-.475 2.923");
}

.gcvwq2btm {
  d: path("M12 8h3v20h-3zm9 0h3v20h-3z");
}

.jne663b5e {
  d: path("M17.999 9.5c-8.15 0-11.342-1.033-11.474-1.077a1.5 1.5 0 0 1 .94-2.849c.046.014 3.006.926 10.534.926c7.551 0 10.506-.916 10.534-.926a1.507 1.507 0 0 1 1.888.961a1.496 1.496 0 0 1-.947 1.887c-.132.044-3.326 1.078-11.475 1.078");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

</style>
