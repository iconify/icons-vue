<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfio0nn0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:devices-sharp" /></template>
<style>
.pfio0nn0w {
  fill: currentColor;
  d: path("M4 16.616V5h15.846v1H12.04v10.616zM14.808 19V8.77h6.384V19zM3 19v-1h9.039v1zm14.997-6.5q.29 0 .483-.2q.193-.202.193-.47q0-.29-.193-.483t-.488-.193q-.273 0-.469.193t-.196.488q0 .273.2.469q.201.196.47.196");
}

</style>
