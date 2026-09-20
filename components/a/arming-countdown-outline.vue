<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr45p43mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arming-countdown-outline" /></template>
<style>
.qr45p43mi {
  fill: currentColor;
  d: path("M12 15.5q1.667 0 2.833-1.166T16 11.502t-1.167-2.834Q13.667 7.5 12 7.5v.885q1.308 0 2.212.903q.904.904.904 2.212t-.91 2.212t-2.206.904q-.79 0-1.472-.387t-1.14-1.035l-.722.495q.58.83 1.443 1.32T12 15.5m-3.558-3.015q.287 0 .5-.213t.212-.499t-.213-.499t-.508-.213t-.5.202q-.202.2-.202.508t.201.51t.51.203m.992-2.283q.212-.203.212-.499t-.201-.509t-.51-.212t-.51.212q-.202.213-.202.509t.213.499t.499.203t.499-.203m.912-1.21q.287 0 .5-.213t.212-.5t-.213-.498t-.508-.213t-.5.201q-.202.201-.202.509t.201.51t.51.203M12 20.963q-3.014-.895-5.007-3.651T5 11.1V5.692l7-2.615l7 2.615V11.1q0 3.454-1.993 6.21T12 20.963m0-1.062q2.6-.825 4.3-3.3t1.7-5.5V6.375l-6-2.23l-6 2.23V11.1q0 3.025 1.7 5.5t4.3 3.3m0-7.88");
}

</style>
