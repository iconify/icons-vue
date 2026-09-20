<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah5h8zp9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:light-mode-auto-outline-sharp" /></template>
<style>
.ah5h8zp9n {
  fill: currentColor;
  d: path("M1.5 12.5v-1H5v1zm10-7.5V1.5h1V5zm0 17.5V19h1v3.5zM6.746 7.404l-2.16-2.098l.695-.745l2.111 2.135zM18.72 19.439l-2.117-2.141l.652-.702l2.16 2.098zm-13.432-.006l-.725-.714l2.14-2.117l.664.652zM12 16q-1.671 0-2.835-1.164Q8 13.67 8 12t1.165-2.835T12 8q.237 0 .467.028t.448.078l-.348.958q-.138-.045-.274-.054Q12.158 9 12 9q-1.25 0-2.125.875T9 12t.875 2.125T12 15q.86 0 1.565-.447q.704-.447 1.087-1.168h1.075q-.408 1.148-1.418 1.881Q13.3 16 12 16m2.377-5l3.47-9h.73l3.508 9H21.03l-1.008-2.539H16.4L15.392 11zm2.32-3.35h3.03l-1.496-3.996h-.077z");
}

</style>
