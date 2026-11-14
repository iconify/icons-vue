<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr25rob3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:binary-star" /></template>
<style>
.fr25rob3j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.287 16.396q.847.104 1.713.104q.296 0 .592-.012q.295-.013.588-.037q.293-.025.582-.061q.289-.037.572-.086t.559-.109t.544-.131t.525-.155q.257-.082.503-.175t.479-.196q.232-.103.451-.215q.219-.113.422-.234q.204-.121.39-.25q.187-.13.357-.266q.169-.137.32-.28t.282-.293q.132-.149.244-.304m-6.709-6.179Q12.351 7.5 12 7.5q-.181 0-.361.005q-.18.004-.36.013t-.359.023t-.356.032q-.178.018-.354.041t-.35.05t-.345.059q-.172.031-.341.067t-.335.076t-.328.085q-.163.044-.321.092q-.159.049-.314.101q-.154.052-.305.108q-.15.057-.296.117t-.286.123t-.277.131q-.135.067-.265.138q-.13.07-.254.144t-.242.15q-.119.077-.23.157t-.218.162q-.105.083-.204.168t-.19.172t-.176.177t-.162.182t-.147.185q-.07.094-.133.189q-.062.096-.117.192q-.054.097-.101.195t-.086.198t-.069.199t-.054.201M12 12h.01m3.49-4a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-12 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
