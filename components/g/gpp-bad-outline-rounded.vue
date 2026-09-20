<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf9a5_bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gpp-bad-outline-rounded" /></template>
<style>
.pf9a5_bdy {
  fill: currentColor;
  d: path("m12 12.63l1.746 1.747q.14.14.344.15t.364-.15t.16-.354t-.16-.354l-1.746-1.746l1.746-1.746q.14-.14.15-.344t-.15-.364t-.354-.16t-.354.16L12 11.216l-1.746-1.747q-.14-.14-.344-.15t-.364.15t-.16.354t.16.354l1.746 1.746l-1.746 1.746q-.14.14-.15.344t.15.364t.354.16t.354-.16zm-.287 8.187q-.15-.025-.28-.075q-2.952-1.125-4.692-3.816T5 11.1V6.817q0-.51.295-.923t.755-.6l5.385-2q.292-.106.565-.106t.566.106l5.384 2q.46.187.755.6t.295.923V11.1q0 3.135-1.74 5.826t-4.693 3.816q-.13.05-.28.075t-.287.025t-.287-.025M12 19.9q2.6-.825 4.3-3.3t1.7-5.5V6.798q0-.192-.106-.346q-.105-.154-.298-.23l-5.384-2q-.096-.04-.212-.04t-.212.04l-5.384 2q-.193.076-.298.23Q6 6.606 6 6.798V11.1q0 3.025 1.7 5.5t4.3 3.3m0-7.861");
}

</style>
