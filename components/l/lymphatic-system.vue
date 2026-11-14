<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="git6y7boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lymphatic-system" /></template>
<style>
.git6y7boh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 5.5q0-3.75 3.25-3.75t3.25 3.75q0 1.812-.759 2.749q.363-.094.803-.22q1.834-.524 2.577-.559q.761-.037 1.229.259q.342.217.504.557q2.646.33 2.646 3.714t-2.646 3.714q-.162.34-.504.557q-.468.296-1.229.259q-.743-.035-2.577-.559q-.44-.126-.803-.22q.759.937.759 2.749q0 3.75-3.25 3.75T5.25 18.5q0-3.384 2.646-3.714q.162-.34.504-.557q.468-.296 1.229-.259q.743.035 2.577.559q.44.126.803.22q-.759-.937-.759-2.749t.759-2.749q-.363.094-.803.22q-1.834.524-2.577.559q-.761.037-1.229-.259q-.342-.217-.504-.557Q5.25 8.884 5.25 5.5");
}

</style>
