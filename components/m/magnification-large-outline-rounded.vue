<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eghyu7unb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:magnification-large-outline-rounded" /></template>
<style>
.eghyu7unb {
  fill: currentColor;
  d: path("M6.308 14.5h9.384q.349 0 .578-.23t.23-.578V8.308q0-.348-.23-.578t-.578-.23H6.308q-.348 0-.578.23t-.23.578v5.384q0 .349.23.578t.578.23M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm0-1h14.769q.23 0 .423-.192t.192-.424V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616v10.769q0 .23.192.423t.423.192M4 18V6z");
}

</style>
