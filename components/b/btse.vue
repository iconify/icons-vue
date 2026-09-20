<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGtuEfVbvf)" class="x2fqhdbcg"/><defs><linearGradient id="SVGtuEfVbvf" x1="5.454" x2="19.897" y1="2.357" y2="20.842" gradientUnits="userSpaceOnUse"><stop class="e05jcvhqi"/><stop offset="1" class="iihd5kbqv"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:btse" /></template>
<style>
.e05jcvhqi {
  stop-color: var(--svg-color--007cd0, #007cd0);
}

.ft5dv1b6b {
  fill: none;
}

.iihd5kbqv {
  stop-color: var(--svg-color--004eae, #004eae);
}

.x2fqhdbcg {
  d: path("M12.373 17.4c1.527 0 2.407-.773 2.407-1.8c0-.952-.777-1.8-2.46-1.8H9v3.6zm-.673-7.2c1.527 0 2.33-.774 2.33-1.8c0-.951-.829-1.8-2.33-1.8H9v3.6zM4.2 3h8.69c2.277 0 3.882.786 4.943 1.813c.724.702 1.164 1.628 1.164 2.83v.049c0 2.03-1.19 3.23-2.794 3.907c2.2.702 3.597 1.903 3.597 4.282v.05c0 3.006-2.536 5.069-6.858 5.069H4.2z");
}

</style>
