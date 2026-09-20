<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtnnf9ljj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:import-contacts-sharp" /></template>
<style>
.xtnnf9ljj {
  fill: currentColor;
  d: path("M12.5 17.32q1.216-.68 2.453-.98t2.547-.302q.9 0 1.849.17t1.651.469V6.681q-.69-.389-1.597-.554T17.5 5.962q-1.31 0-2.613.386q-1.304.387-2.387 1.16zm-.5 1.45q-1.22-.836-2.62-1.283t-2.88-.448q-1.229 0-2.42.345q-1.19.347-2.08.916V6.07q.85-.52 2.04-.814Q5.229 4.96 6.5 4.96q1.47 0 2.866.423q1.398.424 2.634 1.231q1.237-.807 2.634-1.23t2.866-.423q1.271 0 2.451.294T22 6.069V18.3q-.885-.57-2.078-.915q-1.193-.347-2.422-.347q-1.48 0-2.88.448T12 18.77");
}

</style>
