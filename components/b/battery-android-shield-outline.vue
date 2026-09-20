<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs77mab3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-shield-outline" /></template>
<style>
.gs77mab3u {
  fill: currentColor;
  d: path("M4.385 17q-1 0-1.693-.692T2 14.616V9.385q0-1 .692-1.693T4.385 7h10.842l-2.92 1H4.386q-.58 0-.982.403Q3 8.806 3 9.385v5.23q0 .58.403.982q.403.403.982.403h10.311q.214.287.435.527t.488.473zM3 16V8zm15.5.23q-1.654-.609-2.73-2.516T14.691 9.46q.756-.028 1.673-.432q.918-.404 2.135-1.26q1.217.856 2.135 1.26t1.673.432q0 2.345-1.077 4.252t-2.73 2.52m0-1.09q1.067-.537 1.827-1.874q.76-1.336.932-2.973q-.594-.142-1.268-.468T18.5 8.971z");
}

</style>
