<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wla7krbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:estate-planning" /></template>
<style>
.wla7krbmd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.935 9.143L9.81 4.132q2.19-1.866 4.38 0l5.875 5.011q1.185 1.011 1.185 2.568v1.461l-.072-.073Q20.079 12 18.525 12H17.25q-3.75 0-3.75 3.75v4q0 .812.3 1.5H6.125q-3.375 0-3.375-3.375v-6.164q0-1.557 1.185-2.568M17.25 13.25h1.275q1.036 0 1.769.733l1.223 1.224q.733.732.733 1.768v2.775q0 1.036-.732 1.768t-1.768.732h-2.5q-1.036 0-1.768-.732t-.732-1.768v-4q0-2.5 2.5-2.5m0 1.5q-1 0-1 1v4q0 .414.293.707t.707.293h2.5q.414 0 .707-.293t.293-.707v-2.775q0-.415-.293-.708l-1.225-1.224q-.292-.293-.707-.293zM17.5 16v3.5h2v-2.422L18.422 16z");
}

</style>
