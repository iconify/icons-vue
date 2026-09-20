<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byau40q8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dock" /></template>
<style>
.byau40q8l {
  fill: currentColor;
  d: path("M12.04 6.308q.327 0 .548-.222q.22-.221.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.548t.549.22m5.152-2.692v2.126q.31-.001.52.242t.211.549v1.28q0 .307-.21.55q-.211.243-.52.24v7.782q0 .666-.475 1.14T15.577 18H8.423q-.666 0-1.14-.475t-.475-1.14V3.615q0-.666.474-1.14T8.423 2h7.154q.666 0 1.14.475t.475 1.14M8.5 21.52v-1h7v1z");
}

</style>
