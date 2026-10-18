<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cls-1 xrod8fbji"/><path class="cls-2 yr1b83gkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-rome" /></template>
<style>
.xrod8fbji {
  fill: var(--svg-color--27272a, #27272a);
  d: path("M12.84 6.867a.727.727 0 0 1-.413.999C8.734 9.177 6.1 12.567 6.1 16.542v.728H1.935v-.728c0-5.631 3.694-10.437 8.899-12.343a.727.727 0 0 1 .907.37zM1.935 18.658h4.166v11.109H1.935zm27.772-2.116v.728h-4.166v-.728c0-3.975-2.63-7.364-6.325-8.676a.727.727 0 0 1-.415-1l1.098-2.3a.727.727 0 0 1 .907-.37c5.208 1.909 8.901 6.717 8.901 12.346m-4.166 2.116h4.166v11.109h-4.166z");
}

.yr1b83gkl {
  fill: var(--svg-color--ffc905, #ffc905);
  d: path("M18.464 2.174a.73.73 0 0 1 .56 1.035l-.2.419l-1.547 3.24a.73.73 0 0 1-.703.412q-.374-.02-.753-.02t-.753.02a.73.73 0 0 1-.702-.412l-1.548-3.24l-.2-.419a.73.73 0 0 1 .56-1.035a19.6 19.6 0 0 1 5.286 0m5.689 14.368v13.225h-4.166V16.542c0-2.191-1.865-3.967-4.166-3.967s-4.165 1.774-4.165 3.967v13.225H7.49V16.542c0-4.382 3.73-7.935 8.331-7.935s8.332 3.553 8.332 7.935");
}

</style>
