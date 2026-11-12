<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="f5ogxjm1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-2x2-bold-duotone" /></template>
<style>
.dm03gzbnp {
  fill: currentColor;
  d: path("M2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.f5ogxjm1y {
  fill: currentColor;
  d: path("M12.75 2.00098V11.2451H21.999C21.9993 11.4898 22 11.7414 22 12C22 12.2552 21.9993 12.5035 21.999 12.7451H12.75V21.998C12.5068 21.9983 12.2569 22 12 22C11.7431 22 11.4932 21.9983 11.25 21.998V12.7451H2.00098C2.00074 12.5035 2 12.2552 2 12C2 11.7414 2.00073 11.4898 2.00098 11.2451H11.25V2.00098C11.4932 2.00074 11.7431 2 12 2C12.2569 2 12.5068 2.00074 12.75 2.00098Z");
}

</style>
