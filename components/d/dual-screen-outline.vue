<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5uu0wbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dual-screen-outline" /></template>
<style>
.z5uu0wbvi {
  fill: currentColor;
  d: path("m7.154 17.177l4.769 2.477q.308.115.577-.058q.27-.173.27-.5V6.804q0-.192-.107-.346q-.105-.154-.279-.231L6.77 4v13.177zm-.368 1.498q-.457-.18-.737-.586t-.28-.912V4.039q0-.441.3-.74T6.807 3l5.93 2.314q.457.18.744.593t.287.916v12.273q0 .873-.711 1.35t-1.506.156zM12.769 18v-1h3.847q.269 0 .442-.173t.173-.442V4.615q0-.269-.173-.442T16.616 4H6.808V3h9.805q.674 0 1.146.475q.472.474.472 1.14v11.77q0 .666-.475 1.14t-1.14.475zm-6-.823V4z");
}

</style>
