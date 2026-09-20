<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcryxwj1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contact-page-sharp" /></template>
<style>
.bcryxwj1g {
  fill: currentColor;
  d: path("M12 13.539q.633 0 1.066-.434t.434-1.066t-.434-1.067q-.433-.433-1.066-.433t-1.066.433t-.434 1.067t.434 1.066q.433.434 1.066.434m-3.5 3.384h7v-.152q0-.465-.248-.792t-.67-.52q-.61-.275-1.263-.405T12 14.923t-1.32.13t-1.263.407q-.42.192-.669.519q-.248.327-.248.792zM19 21H5V3h8.577L19 8.423z");
}

</style>
