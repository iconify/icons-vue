<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="z8obxkbmv"/><path class="yt74awoyn"/><path class="gf4y3ibnv"/><path class="zu-x4byov"/><path class="jvmjambnp"/><path class="o-6sx9bbk"/><path class="jgot4ybnc"/><path class="w-9wnac4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:lower-left-pencil" /></template>
<style>
.gf4y3ibnv {
  fill: var(--svg-color--e58732, #e58732);
  d: path("m15.12 51.811l-6.982-5.194l-1 8.653l-1.01 8.628l7.986-3.448l7.99-3.44z");
}

.jgot4ybnc {
  fill: var(--svg-color--f79420, #f79420);
  d: path("m9.386 57.684l.804.596l7.06-4.88l-5.208-3.88z");
}

.jvmjambnp {
  fill: var(--svg-color--bcbdbf, #bcbdbf);
  d: path("M52.575 16.05L38.606 5.66l1.123-1.51l13.969 10.39z");
}

.o-6sx9bbk {
  fill: var(--svg-color--e7e6e6, #e7e6e6);
  d: path("M37.475 7.167L51.44 17.565l1.13-1.515L38.599 5.662zm16.219 7.377L39.722 4.152l1.123-1.51l13.972 10.392z");
}

.w-9wnac4z {
  fill: var(--svg-color--424143, #424143);
  d: path("m14.497 60.28l-.387.16l-7.991 3.456l1.01-8.636l.051-.428z");
}

.yt74awoyn {
  fill: var(--svg-color--da4241, #da4241);
  d: path("m22.1 57.003l-4.854-3.612L49.76 9.69l4.854 3.611zm-10.056-7.477L8.136 46.62L40.633 2.909l3.908 2.905z");
}

.z8obxkbmv {
  fill: var(--svg-color--ee4237, #ee4237);
  d: path("M22.101 57.008L8.131 46.614L40.642 2.912l13.972 10.395z");
}

.zu-x4byov {
  fill: var(--svg-color--ea97bd, #ea97bd);
  d: path("M41.558 1.682c-1.326 1.778-.903 4.335.944 5.71l7.284 5.417c1.847 1.378 4.416 1.043 5.741-.734c1.329-1.783.903-4.34-.944-5.711L47.3.943c-1.846-1.375-4.419-1.044-5.742.739");
}

</style>
