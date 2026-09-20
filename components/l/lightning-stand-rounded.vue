<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yycrxwqth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lightning-stand-rounded" /></template>
<style>
.yycrxwqth {
  fill: currentColor;
  d: path("M11.154 9.77h-.996q-.237 0-.358-.193q-.121-.192.01-.404l2.657-4.656q.081-.136.23-.106t.15.193v3.473h.995q.237 0 .358.192t-.01.404l-2.657 4.656q-.081.136-.23.105q-.15-.03-.15-.192zM6.932 20.948Q5.23 20.129 5.23 18.5q0-.956.402-1.527q.401-.571 1.11-.842q-.247.142-.383.42q-.135.278-.135.666q0 .681.447 1.164t1.227.786t1.834.453q1.053.15 2.267.15t2.267-.15t1.834-.453t1.227-.786q.447-.483.447-1.164q0-.388-.135-.666q-.136-.278-.382-.42q.708.271 1.11.842q.401.571.401 1.527q0 1.629-1.7 2.449t-5.069.82t-5.068-.82m1.466-2.477Q7 17.944 7 17.115q0-.817 1.407-1.35T12 15.23q2.204 0 3.602.528T17 17.116q0 .828-1.398 1.356T12 19t-3.602-.528");
}

</style>
