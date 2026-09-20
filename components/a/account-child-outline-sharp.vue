<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btpongbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:account-child-outline-sharp" /></template>
<style>
.btpongbdu {
  fill: currentColor;
  d: path("M15.503 3.71q1.64.711 2.858 1.93t1.929 2.855t.71 3.5t-.71 3.505t-1.93 2.86t-2.855 1.93t-3.5.71t-3.502-.707t-2.864-1.932t-1.931-2.864T3 11.995t.71-3.5T5.64 5.64t2.862-1.93T12.005 3t3.498.71m2.16 13.953Q20 15.325 20 12t-2.337-5.663T12 4T6.337 6.338T4 12t2.338 5.663T12 20t5.663-2.337m-7.355-9.894q0 .71.491 1.201q.492.491 1.201.491t1.201-.49q.491-.492.491-1.202t-.491-1.2T12 6.076t-1.201.491t-.491 1.201m-.769 3.089q-1.347.55-1.347 1.565v3.385q0 .945 1.335 1.59q1.334.644 2.896.514v-1.7q-.73.043-1.375-.106q-.646-.148-1.163-.46q.086-.479.74-.793T12 14.539t1.418.323t.698.819v1.858q.907-.304 1.3-.78q.392-.476.392-.951v-3.385q0-1.015-1.347-1.565T12 10.308t-2.46.55m1.707 2.95q-.305-.308-.305-.753t.308-.75t.753-.305t.75.308t.305.752t-.308.75t-.753.305t-.75-.307M12 12");
}

</style>
