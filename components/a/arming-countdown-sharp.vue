<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-akm-1bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arming-countdown-sharp" /></template>
<style>
.g-akm-1bj {
  fill: currentColor;
  d: path("M12 15.5q1.664 0 2.832-1.168T16 11.5t-1.168-2.832T12 7.5v.885q1.308 0 2.212.903q.904.904.904 2.212t-.904 2.212t-2.212.904q-.787 0-1.47-.387q-.684-.387-1.141-1.035l-.723.495q.58.83 1.447 1.32T12 15.5m-3.558-3.015q.287 0 .5-.213t.212-.499t-.213-.499t-.499-.213q-.306 0-.508.203q-.203.203-.203.509t.203.509t.508.202m.992-2.283q.212-.203.212-.49q0-.305-.203-.518q-.202-.212-.508-.212t-.509.212t-.203.518q0 .287.213.49q.212.203.499.203q.286 0 .499-.203m.912-1.21q.287 0 .5-.213t.212-.5t-.213-.498t-.499-.213q-.305 0-.508.203t-.203.509t.203.508t.508.203M12 20.963q-3.014-.895-5.007-3.651T5 11.1V5.692l7-2.615l7 2.615V11.1q0 3.454-1.993 6.21T12 20.963");
}

</style>
