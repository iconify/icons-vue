<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcapinbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:architecture" /></template>
<style>
.kcapinbhw {
  fill: currentColor;
  d: path("M7.135 19.923L7 18.877l2.58-7.12q.203.178.419.28q.217.104.447.17l-2.519 6.974zm9.73 0l-.792-.742l-2.52-6.973q.232-.067.448-.17t.418-.28L17 18.877zM10.232 9.769Q9.5 9.04 9.5 8q0-.975.61-1.632q.611-.657 1.39-.784V3h1v2.585q.779.127 1.39.783q.61.657.61 1.632q0 1.039-.73 1.77T12 10.5t-1.77-.73m2.829-.711Q13.5 8.617 13.5 8t-.441-1.059Q12.617 6.5 12 6.5t-1.059.441T10.5 8t.441 1.059Q11.383 9.5 12 9.5t1.059-.441");
}

</style>
