<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2y-e6bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:engaged-couple" /></template>
<style>
.o2y-e6bho {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.836 2.25h-3.672q-.995 0-1.665.737l-.867.954Q7.197 4.42 7.084 5h9.832q-.113-.58-.548-1.059l-.867-.954q-.67-.737-1.665-.737m2.87 4.25H7.294q.257.502.776.84l1.866 1.213q-1.506.471-2.709 1.674Q5.25 12.204 5.25 15t1.977 4.773T12 21.75t4.773-1.977T18.75 15t-1.977-4.773q-1.203-1.203-2.709-1.674L15.93 7.34q.519-.338.776-.84");
}

</style>
