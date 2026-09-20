<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jee_knbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:infrared-outline-sharp" /></template>
<style>
.jee_knbtv {
  fill: currentColor;
  d: path("m14.246 20.246l-.713-.713q1.458-1.458 2.289-3.39q.832-1.931.832-4.143t-.832-4.143t-2.29-3.39l.714-.713q1.592 1.592 2.5 3.707T17.654 12t-.908 4.54t-2.5 3.706m-2.402-2.402l-.713-.713q.984-.985 1.561-2.3q.577-1.316.577-2.831t-.577-2.83t-1.561-2.3l.713-.714q1.12 1.119 1.772 2.617q.653 1.498.653 3.227t-.653 3.227q-.652 1.498-1.772 2.617m-2.382-2.383l-.714-.713q.53-.53.834-1.237q.303-.705.303-1.511t-.303-1.511t-.834-1.237l.714-.713q.665.665 1.044 1.553T10.885 12t-.38 1.908t-1.043 1.554M5.019 19.5v-15h1v6q.614.02 1.047.453q.434.434.434 1.047t-.434 1.047t-1.047.453v6z");
}

</style>
