<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="cxryjirvv"/><path class="gg0mo6bno"/><path class="o_p08qbob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-seedkit" /></template>
<style>
.cxryjirvv {
  fill: var(--svg-color--4f51e5, #4f51e5);
  d: path("M29.6 5.5H18.2l-2.1 4.2H4.4v16.8h25.2zm-2.1 4.2h-8.2l1.1-2.1h7.1z");
}

.ft5dv1b6b {
  fill: none;
}

.gg0mo6bno {
  fill: var(--svg-color--4f51e5, #4f51e5);
  d: path("M16 18.194c0-1.118 0-1.677.218-2.104c.192-.376.498-.681.874-.872C17.52 15 18.08 15 19.2 15h3.6c1.12 0 1.68 0 2.108.218c.376.191.682.496.874.872c.218.427.218.986.218 2.104v3.594c0 1.118 0 1.677-.218 2.104a2 2 0 0 1-.874.873c-.428.218-.988.218-2.108.218h-3.6c-1.12 0-1.68 0-2.108-.218a2 2 0 0 1-.874-.873C16 23.465 16 22.906 16 21.788z");
}

.o_p08qbob {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.2 20.33a.14.14 0 0 1 .139-.14H23a1.798 1.798 0 1 1 0 3.594c-.994 0-1.8-.804-1.8-1.796zm0-.677c0 .077.062.139.139.139H23a1.798 1.798 0 1 0 0-3.594c-.994 0-1.8.804-1.8 1.797zm-.4.677a.14.14 0 0 0-.139-.14H19a1.798 1.798 0 1 0 0 3.594c.994 0 1.8-.804 1.8-1.796zm0-.677a.14.14 0 0 1-.139.139H19a1.798 1.798 0 1 1 0-3.594c.994 0 1.8.804 1.8 1.797z");
}

</style>
