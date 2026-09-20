<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tilekmbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gamepad-circle-down-outline-rounded" /></template>
<style>
.tilekmbdi {
  fill: currentColor;
  d: path("M9.766 20.08q-.92-.918-.92-2.234t.92-2.234q.919-.92 2.234-.92t2.235.92t.919 2.234t-.92 2.235Q13.317 21 12 21t-2.234-.92m0-11.692q-.92-.919-.92-2.234q0-1.316.92-2.235Q10.683 3 12 3t2.235.92q.919.919.919 2.234t-.92 2.235q-.918.919-2.234.919t-2.234-.92m3.758-.708q.63-.627.63-1.524t-.628-1.526T12.002 4t-1.526.628t-.63 1.524t.628 1.526t1.524.63t1.526-.628m-7.37 7.474q-1.307 0-2.23-.92Q3 13.317 3 12t.924-2.234q.923-.92 2.23-.92t2.23.92T9.308 12t-.924 2.235q-.923.919-2.23.919m-.002-1q.896 0 1.526-.628q.63-.627.63-1.524t-.628-1.526t-1.524-.63t-1.526.628T4 11.998t.628 1.526t1.524.63m11.674 1q-1.314 0-2.224-.92q-.91-.918-.91-2.234t.91-2.234q.91-.92 2.224-.92t2.245.92Q21 10.683 21 12t-.93 2.235q-.929.919-2.244.919m.004-1q.891 0 1.53-.628q.64-.627.64-1.524t-.64-1.526t-1.53-.63q-.89 0-1.514.628q-.624.627-.624 1.524t.624 1.526t1.514.63");
}

</style>
