<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehrezhbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrows-up-down-circle-outline-rounded" /></template>
<style>
.ehrezhbmf {
  fill: currentColor;
  d: path("M8.494 20.299q-1.642-.701-2.867-1.926t-1.926-2.867T3 12t.701-3.506t1.926-2.857T8.494 3.71T12 3t3.506.71t2.857 1.927t1.926 2.857T21 12t-.71 3.506t-1.926 2.867t-2.858 1.926T12 21t-3.506-.701M12 20q3.325 0 5.663-2.328T20 12q0-3.325-2.337-5.663T12 4Q8.656 4 6.328 6.338T4 12q0 3.344 2.328 5.672T12 20m-.5-4.377l-1.611-1.611q-.141-.14-.345-.14t-.344.14q-.16.14-.15.354t.15.353l2.235 2.235q.242.242.565.242t.566-.242l2.253-2.235q.14-.14.15-.354t-.15-.354q-.14-.14-.353-.14q-.214 0-.354.14L12.5 15.624V8.396l1.612 1.592q.14.14.344.15t.363-.15t.16-.353t-.16-.354l-2.254-2.215q-.242-.243-.565-.243t-.565.243L9.2 9.28q-.16.14-.16.344t.16.364q.16.159.354.159t.354-.16l1.592-1.59z");
}

</style>
