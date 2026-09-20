<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce7z4pber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:health-and-safety-rounded" /></template>
<style>
.ce7z4pber {
  fill: currentColor;
  d: path("M11 12.5v1.98q0 .214.153.367t.366.153h.962q.233 0 .376-.153t.143-.366V12.5h1.98q.234 0 .377-.153t.143-.366v-.962q0-.233-.143-.376t-.376-.143H13V8.52q0-.234-.143-.377T12.48 8h-.962q-.213 0-.366.143T11 8.52v1.98H9.02q-.214 0-.367.143t-.153.376v.962q0 .213.153.366t.366.153zm.714 8.317q-.15-.025-.281-.075q-2.952-1.125-4.692-3.816T5 11.1V6.817q0-.51.295-.923t.755-.6l5.385-2q.292-.106.565-.106t.566.106l5.384 2q.46.187.755.6t.295.923V11.1q0 3.135-1.74 5.826t-4.693 3.816q-.13.05-.28.075t-.287.025t-.287-.025");
}

</style>
