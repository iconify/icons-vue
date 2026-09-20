<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-8__me-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-outline-rounded" /></template>
<style>
.g-8__me-j {
  fill: currentColor;
  d: path("m12 16.923l-3.738 1.608q-.808.348-1.535-.134Q6 17.916 6 17.052V5.616q0-.691.463-1.153T7.616 4h8.769q.69 0 1.153.463T18 5.616v11.436q0 .864-.727 1.345q-.727.482-1.535.134zm0-1.123l4.135 1.784q.307.135.586-.057q.279-.193.279-.52V5.617q0-.231-.192-.424T16.384 5H7.616q-.231 0-.424.192T7 5.616v11.392q0 .327.279.519t.586.057zM12 5H7h10z");
}

</style>
