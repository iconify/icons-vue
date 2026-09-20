<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnd7gg67n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:3d-2-outline" /></template>
<style>
.jnd7gg67n {
  fill: currentColor;
  d: path("M12.154 16.217V7.712h2.844q1.887 0 2.876 1.153q.99 1.152.99 3.097t-.993 3.1t-2.873 1.155zm.971-.953h1.856q1.458 0 2.185-.894q.726-.893.726-2.408q0-1.516-.726-2.409q-.727-.894-2.185-.894h-1.856zm-5.264 1.14q-1.128 0-1.823-.58t-.825-1.678l.916-.254q.125.745.566 1.167t1.186.422q.757 0 1.192-.445t.435-1.197q0-.708-.498-1.172q-.499-.463-1.304-.463H7.02v-.908h.654q.692 0 1.125-.408t.433-1.04t-.401-1.028t-1.078-.395q-.613 0-1.005.348t-.522.962l-.91-.123q.123-.98.79-1.533q.668-.554 1.652-.554q1.068 0 1.757.61q.69.611.69 1.61q0 .653-.318 1.137t-.869.776v.061q.673.256 1.064.831q.39.575.39 1.323q0 1.187-.707 1.859q-.706.672-1.904.672");
}

</style>
