<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovnq_6qim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gpp-maybe-rounded" /></template>
<style>
.ovnq_6qim {
  fill: currentColor;
  d: path("M12.434 15.049q.182-.182.182-.433q0-.252-.182-.434T12 14t-.434.182t-.182.433t.182.434t.434.182t.434-.182m-.077-2.77q.143-.142.143-.356V8.269q0-.213-.143-.357T12 7.77t-.357.143t-.143.357v3.654q0 .214.143.357t.357.143t.357-.143m-.643 8.537q-.15-.025-.281-.075q-2.952-1.125-4.692-3.816T5 11.1V6.817q0-.51.295-.923t.755-.6l5.385-2q.292-.106.565-.106t.566.106l5.384 2q.46.187.755.6t.295.923V11.1q0 3.135-1.74 5.826t-4.693 3.816q-.13.05-.28.075t-.287.025t-.287-.025");
}

</style>
