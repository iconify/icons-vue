<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea8a-abct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:attach-file-sharp" /></template>
<style>
.ea8a-abct {
  fill: currentColor;
  d: path("M17.346 15.539q0 2.272-1.565 3.867Q14.216 21 11.96 21q-2.272 0-3.847-1.594t-1.575-3.867V6.808q0-1.587 1.09-2.697Q8.722 3 10.309 3t2.678 1.11t1.091 2.698v8.269q0 .88-.617 1.517q-.618.637-1.499.637t-1.517-.627t-.636-1.527V6.769h1v8.308q0 .479.327.816q.328.338.807.338t.807-.338t.328-.816V6.789q-.006-1.166-.805-1.977T10.308 4t-1.967.821t-.802 1.987v8.73q-.006 1.853 1.282 3.157T11.961 20q1.828 0 3.1-1.305t1.285-3.156v-8.77h1z");
}

</style>
