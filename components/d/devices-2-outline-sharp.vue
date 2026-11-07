<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf3tsubna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:devices-2-outline-sharp" /></template>
<style>
.tf3tsubna {
  fill: currentColor;
  d: path("M3 19V5h18.192v1H4v12h8.039v1zm17.192-1V9.77h-4.384V18zm-5.384 1V8.77h6.384V19zm3.189-6.5q.29 0 .483-.2q.193-.202.193-.47q0-.29-.193-.483t-.488-.193q-.273 0-.469.193t-.196.488q0 .273.2.469q.201.196.47.196M18 13.885");
}

</style>
