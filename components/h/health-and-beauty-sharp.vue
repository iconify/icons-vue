<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5rhsgb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:health-and-beauty-sharp" /></template>
<style>
.o5rhsgb1k {
  fill: currentColor;
  d: path("M16.039 21v-1h4v-2.77h-4v-1h4v-2.768h-4v-1h4v-2.77h-4v-1h4V5.923h-4v-1h5.769V21zM5.653 21l-3.462-9.577l4.77-2.846V3h2v5.577l4.769 2.846L10.269 21z");
}

</style>
