<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipj89sb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:devices-other-sharp" /></template>
<style>
.ipj89sb2x {
  fill: currentColor;
  d: path("M3 19V5h18.192v1.385h-8.73v3.23H7.994l-.75 2.668q-.575.65-.89 1.47q-.316.819-.316 1.748t.316 1.748t.89 1.468L7.33 19zm6.808 0l-.442-1.538q-.437-.348-.69-.857t-.253-1.106t.253-1.105t.69-.856L9.808 12h2.23l.443 1.539q.436.347.69.856q.252.509.252 1.106t-.253 1.105t-.69.855L12.04 19zm1.115-1.884q.7 0 1.158-.476t.458-1.14t-.489-1.14t-1.127-.475t-1.127.453t-.488 1.162t.458 1.162q.457.454 1.157.454m7.074-4.616q.29 0 .483-.2q.193-.202.193-.47q0-.29-.193-.483t-.488-.193q-.273 0-.469.193t-.196.488q0 .273.2.469q.201.196.47.196m-3.19 6.5V8.77h6.385V19z");
}

</style>
