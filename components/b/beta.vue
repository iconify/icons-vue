<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGRwk3PbcV)" clip-rule="evenodd" class="yzi36vb0q"/><defs><linearGradient id="SVGRwk3PbcV" x1="20.518" x2="4.607" y1="9.107" y2="18.107" gradientUnits="userSpaceOnUse"><stop class="qm3q7nxtu"/><stop offset="1" class="dnajc-bko"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:beta" /></template>
<style>
.dnajc-bko {
  stop-color: var(--svg-color--ad8bd4, #ad8bd4);
}

.ft5dv1b6b {
  fill: none;
}

.qm3q7nxtu {
  stop-color: var(--svg-color--cd9cbc, #cd9cbc);
}

.yzi36vb0q {
  fill-rule: evenodd;
  d: path("M18.364 18.364A9 9 0 1 1 5.636 5.636a9 9 0 0 1 12.728 12.728M14.001 8.262c-.058-.074.01-.18.1-.153c1.303.365 2.15.963 2.15 1.652c0 1.117-2.26 2.017-5.045 2.017c-1.816 0-3.41-.382-4.294-.964c-.074-.042-.031-.153.053-.138c.673.133 1.43.202 2.224.202c2.784 0 5.045-.9 5.045-2.012c0-.212-.085-.413-.233-.604m.995 3.516c-.068-.085.016-.207.122-.18c1.514.428 2.504 1.133 2.504 1.932c0 1.297-2.636 2.356-5.892 2.356c-2.123 0-3.986-.45-5.019-1.128c-.09-.053-.037-.18.069-.159c.778.154 1.662.239 2.594.239c3.256 0 5.893-1.054 5.893-2.356c0-.244-.096-.482-.27-.704");
}

</style>
