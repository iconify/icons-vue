<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wsxs09byw"/><path class="qe0wo61pa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:appliance-store" /></template>
<style>
.qe0wo61pa {
  d: path("M8 20.5v-5h3.2m2.8-3h8v9.25h-8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wsxs09byw {
  d: path("M11.218 10.205q-.152.131-.324.233t-.361.171q-.188.07-.385.106q-.198.035-.398.035q-.111 0-.221-.011t-.218-.032t-.214-.054t-.208-.074q-.102-.043-.2-.095q-.097-.052-.189-.113t-.177-.132q-.086-.07-.164-.148t-.148-.164t-.132-.177t-.113-.189t-.095-.2q-.042-.102-.074-.208t-.054-.214q-.021-.108-.032-.218T7.5 8.5q0 .111-.011.22q-.011.11-.032.219q-.022.108-.054.214t-.074.208q-.043.102-.095.199t-.113.19t-.132.177t-.148.163t-.164.149q-.085.07-.177.131q-.092.062-.19.114q-.097.052-.199.094t-.208.074t-.214.054q-.109.022-.219.032q-.109.011-.22.011t-.22-.011q-.11-.01-.219-.032q-.108-.022-.214-.054t-.208-.074t-.199-.094T4 10.37q-.092-.061-.177-.131q-.086-.07-.164-.149t-.148-.163t-.132-.177q-.061-.092-.113-.19q-.052-.097-.095-.199q-.042-.102-.074-.208t-.054-.214t-.032-.219Q3 8.611 3 8.5l1.5-5h15l1.5 5q0 .318-.089.624q-.088.305-.258.574m-3.78.041q-.182-.275-.277-.592T16.5 8.5q0 .329-.094.645q-.095.316-.276.591m-3.78-.031q-.172-.271-.261-.578T12 8.5q0 .311-.084.609q-.084.299-.246.564M5.25 10.75v9.75h5.95");
}

</style>
