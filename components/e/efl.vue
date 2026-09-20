<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG1MLmQdLD)" class="rbpe44j4s"/><defs><linearGradient id="SVG1MLmQdLD" x1="6.778" x2="18.52" y1="5.755" y2="17.303" gradientUnits="userSpaceOnUse"><stop class="sqib32b0e"/><stop offset="1" class="nks7ssbqn"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:efl" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nks7ssbqn {
  stop-color: var(--svg-color--f58d0b, #f58d0b);
}

.rbpe44j4s {
  d: path("m10.939 9.16l-2.415-.542l-.189.722l2.345.55c-.627 2.614-2.034 8.148-2.65 9.372c-.757 1.508-1.744 1.332-1.802 1.1a1.125 1.125 0 0 0-.405-2.175a1.13 1.13 0 0 0-1.13 1.076C4.598 20.582 5.93 21 6.847 21c4-.306 6.34-6.996 7.009-10.303l2.41.588l.196-.762l-2.365-.632c1.052-4.97 2.387-6.473 3.153-6.343a.8.8 0 0 1 .372.162a1.125 1.125 0 0 0 .56 2.102a1.128 1.128 0 0 0 1.116-1.305l-.002-.016a1.1 1.1 0 0 0-.195-.46c-.503-.786-1.675-1.047-2.246-1.03c-3.526.144-5.413 4.166-5.916 6.158");
}

.sqib32b0e {
  stop-color: var(--svg-color--ff9b13, #ff9b13);
}

</style>
