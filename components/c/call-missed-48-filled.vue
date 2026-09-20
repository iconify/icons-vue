<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nsa7gbbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:call-missed-48-filled" /></template>
<style>
.nsa7gbbvu {
  fill: currentColor;
  d: path("M42.304 20.174c2.574-3.7 1.916-9.049-2.593-10.99C35.947 7.561 30.606 6 24.001 6S12.053 7.562 8.29 9.183c-4.509 1.942-5.168 7.29-2.593 10.99a4.25 4.25 0 0 0 3.986 1.795l3.166-.372A5.25 5.25 0 0 0 17.23 18l.713-2.201c.23-.712.66-1.11 1.102-1.208c1.277-.286 3.088-.443 4.95-.445c1.864-.002 3.678.151 4.96.44c.443.1.872.5 1.103 1.213L30.77 18a5.25 5.25 0 0 0 4.381 3.596l3.166.372a4.25 4.25 0 0 0 3.986-1.794M25 29.25a1.25 1.25 0 0 0-2.5 0v5.5c0 .69.56 1.25 1.25 1.25h3.5a1.25 1.25 0 0 0 0-2.5H25zM24 44c6.076 0 11-4.925 11-11s-4.924-11-11-11s-11 4.925-11 11s4.925 11 11 11m0-2.5a8.5 8.5 0 1 1 0-17a8.5 8.5 0 0 1 0 17");
}

</style>
