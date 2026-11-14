<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scl5mpp2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ice-climber" /></template>
<style>
.scl5mpp2i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.835 2.329l3 1.5h.001l.002.001q3.222 1.612 4.833 4.835q.067.133.077.282q.011.149-.036.29q-.048.142-.145.254q-.098.113-.232.18q-.066.033-.137.052q-.071.02-.145.025t-.147-.004t-.143-.032t-.134-.06t-.12-.085t-.101-.107t-.079-.125q-1.231-2.463-3.555-3.833l-3.449 5.748h.245q.215 0 .398-.114l2.689-1.682q1.417-.886 2.675.215l2.65 2.319q.768.672.768 1.693V20q0 2.25-2.25 2.25h-15q-2.25 0-2.25-2.25v-5.379q0-.931.659-1.59l2.233-2.233q1.242-1.242 2.748-.338l1.139.683q.179.107.387.107h1.159l3.865-6.441l-2.275-1.138q-.066-.033-.125-.079q-.058-.045-.107-.101q-.048-.055-.085-.12q-.036-.064-.06-.134q-.023-.07-.032-.143t-.004-.147t.025-.145t.052-.137q.067-.134.18-.232q.112-.097.254-.145q.141-.047.29-.036q.149.01.282.077");
}

</style>
