<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq4m0qsmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:allergies-rounded" /></template>
<style>
.dq4m0qsmt {
  fill: currentColor;
  d: path("M9.5 11.25V17q0 .425.288.713T10.5 18t.713-.288t.287-.717v-5.947q0-.136-.038-.273t-.093-.267L9.835 7.457q-.204-.382-.582-.52Q8.875 6.8 8.5 7t-.513.588t.063.762zm5-.006l1.45-2.913q.194-.375.06-.753Q15.875 7.2 15.5 7t-.763-.062t-.587.512l-1.52 3.052q-.055.13-.092.267t-.038.273V17q0 .425.288.713T13.5 18t.713-.288T14.5 17zm2.263 1.818q.387-.137.587-.512l1.1-2.2q.2-.375.063-.762T18 9t-.763-.062t-.587.512l-1.1 2.217q-.2.377-.062.755q.137.378.512.578t.763.063m-8.25-.65q.137-.388-.063-.763l-1.1-2.2q-.2-.375-.587-.513T6 9t-.513.588t.063.762l1.1 2.2q.2.375.588.513T8 13t.513-.587M12.003 21q-1.866 0-3.51-.708q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709");
}

</style>
