<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_vx0g75g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:anchor-point-corner" /></template>
<style>
.x_vx0g75g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 3.25h1q2.25 0 2.25 2.25v1q0 .38-.064.696l.006.016l5 12q.029.068.043.14q.015.073.015.146q0 .074-.014.147q-.014.072-.042.141t-.07.129q-.04.062-.093.114q-.052.053-.113.094t-.13.069q-.068.029-.14.043q-.073.015-.146.015q-.074 0-.147-.014q-.072-.014-.141-.042t-.129-.07q-.062-.04-.114-.093q-.053-.052-.094-.113t-.069-.13L15.627 8.556q-.466.194-1.127.194h-1q-1.683 0-2.107-1.258q-7.442 2.725-8.145 12.561q-.005.074-.025.145q-.019.072-.052.138t-.079.124t-.101.107t-.12.085t-.134.06t-.143.032t-.147.004q-.149-.011-.283-.077q-.133-.067-.231-.18q-.097-.113-.145-.254t-.036-.29q.381-5.332 3.205-9.202q2.544-3.486 6.293-4.79V5.5q0-2.25 2.25-2.25");
}

</style>
