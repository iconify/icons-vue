<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1xmabcfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:isochrone-map" /></template>
<style>
.v1xmabcfs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.789 4.859l4.25-1.771q.961-.401 1.922 0l4.655 1.94q.384.16.769 0l2.904-1.21q1.234-.515 2.348.227t1.113 2.08v10.708q.001 1.667-1.539 2.308l-4.25 1.771q-.961.401-1.922 0l-4.655-1.94q-.384-.16-.769 0l-2.904 1.21q-1.234.515-2.348-.227t-1.113-2.08V7.167Q2.249 5.5 3.789 4.859M12.5 6.75q-6.25 0-6.25 5.25q0 4.815 5.188 5.247q2.769.231 4.282-1.037q1.539-1.291 1.776-4.135q.224-2.237-1.1-3.677q-1.322-1.436-3.834-1.645q-.031-.003-.062-.003");
}

</style>
