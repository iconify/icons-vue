<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj75cdb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dhoti" /></template>
<style>
.fj75cdb7p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 1.75h-9Q5.25 1.75 5.25 4q0 1.396.866 1.926L2.274 20.813q-.037.144-.017.292q.021.147.097.276q.076.128.195.218t.264.127q.221.057.437-.019l4.013-1.416l4.511 1.424q.226.072.452 0l4.511-1.424l4.013 1.416q.07.025.143.035t.147.007t.145-.022t.139-.05q.066-.032.125-.077q.06-.044.109-.099t.087-.118t.062-.133q.076-.216.019-.437L17.884 5.926q.866-.53.866-1.926q0-2.25-2.25-2.25m-3.117 4.5l2.502 12.737L12 20.213l-3.885-1.226L10.617 6.25zm4.02 12.685L14.912 6.25h1.507l3.503 13.574zM7.581 6.25h1.507L6.597 18.935l-2.519.889z");
}

</style>
