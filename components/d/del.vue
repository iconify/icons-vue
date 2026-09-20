<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGnpXQDesW)" class="z5ojhxbbd"/><defs><linearGradient id="SVGnpXQDesW" x1="7.757" x2="19.809" y1="5.571" y2="15.72" gradientUnits="userSpaceOnUse"><stop class="myp3dzior"/><stop offset=".45" class="yd3abrb8c"/><stop offset="1" class="lb42xlbia"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:del" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lb42xlbia {
  stop-color: var(--svg-color--9845f5, #9845f5);
}

.myp3dzior {
  stop-color: var(--svg-color--02fdad, #02fdad);
}

.yd3abrb8c {
  stop-color: var(--svg-color--457df4, #457df4);
}

.z5ojhxbbd {
  d: path("M19.2 3H4.8v3.6H15v10.8H4.8V21h14.4zm-7.8 7.2H4.8v3.6h6.6z");
}

</style>
