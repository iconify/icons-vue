<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGz6LGZdls)" clip-rule="evenodd" class="qqqa0_gae"/><path fill="url(#SVGz6LGZdls)" class="u505wfbdm"/><defs><linearGradient id="SVGz6LGZdls" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="l52_756ao"/><stop offset="1" class="z94d75b3w"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bcmc" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l52_756ao {
  stop-color: var(--svg-color--fcab2f, #fcab2f);
}

.qqqa0_gae {
  fill-rule: evenodd;
  d: path("M12 19.941a7.942 7.942 0 1 0 0-15.883a7.942 7.942 0 0 0 0 15.883M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.u505wfbdm {
  d: path("M12 6.705H8.824V12l1.058-.529V7.764H12a1.589 1.589 0 0 1 .704 3.013C9.792 12.222 6.812 13.583 3.88 15l.466.953l8.01-3.896s1.244-.53 1.599-.921A2.636 2.636 0 0 0 12 6.705m8.587 3.092l-.466-.953l-5.527 2.88a2.119 2.119 0 0 1-1.006 3.982H9.882v-1.763l-1.058.54v2.281h4.764a3.175 3.175 0 0 0 2.69-4.87z");
}

.z94d75b3w {
  stop-color: var(--svg-color--e45e0e, #e45e0e);
}

</style>
