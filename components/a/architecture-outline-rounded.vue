<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3xx14j-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:architecture-outline-rounded" /></template>
<style>
.n3xx14j-h {
  fill: currentColor;
  d: path("M10.446 12.208L7.958 19.08q-.025.056-.125.156l-.32.294q-.128.11-.262.055t-.164-.182l-.081-.421q-.02-.039.025-.206l2.55-7.02q.202.178.418.28q.217.104.447.17m-.215-2.438Q9.5 9.04 9.5 8q0-.975.61-1.632q.611-.657 1.39-.784V3.5q0-.213.143-.357T12 3t.357.143t.143.357v2.085q.779.127 1.39.783q.61.657.61 1.632q0 1.039-.73 1.77T12 10.5t-1.77-.73m2.829-.711Q13.5 8.617 13.5 8t-.441-1.059Q12.617 6.5 12 6.5t-1.059.441T10.5 8t.441 1.059Q11.383 9.5 12 9.5t1.059-.441m.495 3.149q.23-.067.447-.17q.216-.103.399-.28l2.55 7.019q.006.017.025.206l-.08.42q-.032.128-.165.183q-.134.055-.263-.055l-.319-.294l-.125-.156z");
}

</style>
