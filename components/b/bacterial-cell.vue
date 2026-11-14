<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8eajtb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bacterial-cell" /></template>
<style>
.z8eajtb5x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.5 7.25h-4q-1.968 0-3.359 1.391T1.75 12t1.391 3.359T6.5 16.75h4q1.968 0 3.359-1.391q1.325-1.325 1.388-3.173Q15.862 11 16.25 11q.411 0 1.079 1.335Q18.411 14.5 19.75 14.5t2.421-2.165q.067-.133.077-.282q.011-.149-.036-.29q-.048-.142-.145-.254q-.098-.113-.232-.18q-.066-.033-.137-.052q-.071-.02-.145-.025t-.147.004t-.143.032t-.134.06t-.12.085t-.101.107t-.079.125Q20.161 13 19.75 13t-1.079-1.335Q17.589 9.5 16.25 9.5q-.721 0-1.368.628q-.348-.811-1.023-1.487Q12.468 7.25 10.5 7.25");
}

</style>
