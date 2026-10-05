<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z7fs3l-uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-sharp-fill" /></template>
<style>
.z7fs3l-uk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.3857 2.20711C11.7469 1.92603 12.253 1.92603 12.6142 2.20711L23 10.2891L21.7714 11.8673L21 11.2667V21.0001C20.9998 21.5522 20.5521 22.0001 20 22.0001H16V18.0001C16 15.791 14.2091 14.0001 12 14.0001C9.79088 14.0001 7.99996 15.791 7.99996 18.0001V22.0001H3.99996C3.44781 22.0001 3.00014 21.5522 2.99996 21.0001V11.2667L2.22848 11.8673L0.999962 10.2891L11.3857 2.20711Z");
}

</style>
