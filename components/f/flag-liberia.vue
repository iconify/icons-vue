<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="m9agw7gaf"/><path class="p8504u_im"/><path class="nyaq4t_dl"/><path class="p69rkj5sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-liberia" /></template>
<style>
.m9agw7gaf {
  fill: var(--svg-color--bf0a30, #bf0a30);
  d: path("M35.692 28.538H.308A4 4 0 0 0 4 31h28a4 4 0 0 0 3.692-2.462M0 23.811h36v2.561H0zM11.5 9.629H36v2.561H11.5zm24.192-2.167A4 4 0 0 0 32 5H11.5v2.462zM11.5 14.356H36v2.561H11.5zM0 19.083h36v2.561H0z");
}

.nyaq4t_dl {
  fill: var(--svg-color--002868, #002868);
  d: path("M4 5a4 4 0 0 0-4 4v7.917h12V5z");
}

.p69rkj5sw {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.794 10.245L6 7.802l-.794 2.443H2.638l2.078 1.51l-.794 2.443L6 12.688l2.078 1.51l-.794-2.443l2.078-1.51z");
}

.p8504u_im {
  fill: var(--svg-color--eee, #eee);
  d: path("M11.5 12.189H36v2.167H11.5zM0 16.917v2.166h36v-2.166H12zm11.5-9.455v2.167H36V9c0-.545-.111-1.064-.308-1.538zM0 21.644h36v2.167H0zM0 27c0 .545.111 1.064.308 1.538h35.383A4 4 0 0 0 36 27v-.629H0z");
}

</style>
