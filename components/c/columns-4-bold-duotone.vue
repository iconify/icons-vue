<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2-x-cbeh"/><path class="j-2a-nbrj"/><path class="os9vkpw9m"/><path class="yl0s6gb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:columns-4-bold-duotone" /></template>
<style>
.j-2a-nbrj {
  fill: currentColor;
  d: path("M12.75 21H11.25V3H12.75V21Z");
}

.j2-x-cbeh {
  fill: currentColor;
  d: path("M2 11C2 7.22876 2 5.34315 3.17157 4.17157C4.34315 3 6.22876 3 10 3H14C17.7712 3 19.6569 3 20.8284 4.17157C22 5.34315 22 7.22876 22 11V13C22 16.7712 22 18.6569 20.8284 19.8284C19.6569 21 17.7712 21 14 21H10C6.22876 21 4.34315 21 3.17157 19.8284C2 18.6569 2 16.7712 2 13V11Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.os9vkpw9m {
  fill: currentColor;
  d: path("M7.75 20.9844C7.19683 20.9736 6.69936 20.9549 6.25 20.9189V3.08008C6.69935 3.04409 7.19686 3.02538 7.75 3.01465V20.9844Z");
}

.yl0s6gb3b {
  fill: currentColor;
  d: path("M16.25 3.01465C16.8031 3.02538 17.3007 3.04409 17.75 3.08008V20.9189C17.3006 20.9549 16.8032 20.9736 16.25 20.9844V3.01465Z");
}

</style>
