<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib-1_4dtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:closed-caption-add-sharp" /></template>
<style>
.ib-1_4dtz {
  fill: currentColor;
  d: path("M12.923 14.692h3.539q.205-.155.407-.283t.439-.253v-.925h-.885v.577h-2.615v-3.616h2.615v.616h.885v-1.5h-4.385zm-6.23 0h4.384v-1.461h-.885v.577H7.577v-3.616h2.615v.616h.885v-1.5H6.692zM5.615 19q-.691 0-1.153-.462T4 17.384V6.616q0-.691.463-1.153T5.616 5h12.769q.69 0 1.153.463T20 6.616v7.042q-1.071-.16-2.13.237t-1.818 1.157q-.766.765-1.157 1.818T14.658 19zM19 21v-2h-2v-1h2v-2h1v2h2v1h-2v2z");
}

</style>
