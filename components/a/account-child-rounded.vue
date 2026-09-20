<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lick9ab8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:account-child-rounded" /></template>
<style>
.lick9ab8f {
  fill: currentColor;
  d: path("M15.503 3.71q1.64.711 2.858 1.93t1.929 2.855t.71 3.5t-.71 3.505t-1.93 2.86t-2.855 1.93t-3.5.71t-3.502-.707t-2.864-1.932t-1.931-2.864T3 11.995t.71-3.5T5.64 5.64t2.862-1.93T12.005 3t3.498.71m-5.195 4.06q0 .709.491 1.2q.492.491 1.201.491t1.201-.49q.491-.492.491-1.202t-.491-1.2T12 6.076t-1.201.491t-.491 1.201m-.912 3q-1.204.46-1.204 1.66V15.8q0 1.201 1.208 1.656t2.607.454q.36 0 .6-.239q.24-.24.24-.606q0-.368-.244-.607q-.244-.24-.603-.24q-.442.031-.847-.06q-.404-.09-.809-.27q-.217-.087-.283-.302q-.065-.214.072-.395q.364-.37.858-.512T12 14.538q.771 0 1.443.239q.672.238.672.904v.869q0 .254.179.444t.431.19q.498 0 .79-.426q.293-.427.293-.95v-3.376q0-1.203-1.207-1.664t-2.604-.46t-2.6.46m1.85 3.04q-.305-.308-.305-.753t.308-.75t.753-.305t.75.308t.305.752t-.308.75t-.753.305t-.75-.307");
}

</style>
