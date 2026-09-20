<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyyrapbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:height-rounded" /></template>
<style>
.vyyrapbqh {
  fill: currentColor;
  d: path("M11.5 18.06V5.902L9.754 7.629q-.136.14-.339.14t-.353-.146q-.137-.134-.137-.341t.14-.348l2.364-2.363q.137-.137.28-.19t.308-.052t.3.053q.137.052.273.189l2.364 2.363q.14.141.15.332t-.146.357q-.17.165-.361.165t-.357-.165L12.5 5.902V18.06l1.746-1.708q.136-.14.339-.14t.353.146q.137.134.137.34t-.14.348L12.57 19.41q-.136.136-.275.189q-.14.053-.298.053t-.307-.054t-.276-.182l-2.369-2.37q-.134-.135-.14-.339q-.006-.203.14-.353q.134-.137.341-.137t.347.14z");
}

</style>
