<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guzl6ot4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:brightness-alert-sharp" /></template>
<style>
.guzl6ot4y {
  fill: currentColor;
  d: path("M12.434 16.28q.182-.182.182-.434t-.182-.433T12 15.23t-.434.182t-.182.433t.182.434t.434.181t.434-.181m-.934-3.126h1v-6h-1zm.5 8.762L9.069 19H5v-4.069L2.085 12L5 9.069V5h4.069L12 2.085L14.931 5H19v4.069L21.916 12L19 14.931V19h-4.069z");
}

</style>
