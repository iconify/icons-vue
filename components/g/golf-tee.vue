<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jboug8m1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:golf-tee" /></template>
<style>
.jboug8m1s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.288 3.288Q6.75 4.825 6.75 7t1.538 3.712l.038.038H8q-.149 0-.287.057t-.243.163t-.163.243t-.057.287t.057.287t.163.243l2.78 2.781V19q0 .177.079.335l1 2q.055.109.141.195t.195.141q.133.067.282.077q.149.011.29-.036q.142-.048.254-.145q.113-.098.18-.232l1-2q.079-.158.079-.335v-4.189l2.78-2.781q.106-.105.163-.243t.057-.287q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 10.75h-.326l.038-.038Q17.25 9.175 17.25 7t-1.538-3.712Q14.175 1.75 12 1.75T8.288 3.288");
}

</style>
