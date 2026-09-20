<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wir60-s8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:admin-panel-settings-sharp" /></template>
<style>
.wir60-s8h {
  fill: currentColor;
  d: path("M17 21q-1.671 0-2.835-1.164Q13 18.67 13 17t1.165-2.835T17 13t2.836 1.165T21 17t-1.164 2.836T17 21m-5-.039q-3.014-.894-5.007-3.65T5 11.1V5.692l7-2.615l7 2.615v5.656q-.42-.171-.962-.26T17 11q-2.496 0-4.248 1.752T11 17q0 1.03.347 2.011t1.036 1.81l-.192.07zm6.063-4.398q.437-.438.437-1.063t-.437-1.062T17 14t-1.062.438T15.5 15.5t.438 1.063T17 17t1.063-.437M17 20q.794 0 1.435-.353q.64-.353 1.06-.953q-.57-.344-1.195-.519T17 18t-1.3.175t-1.194.52q.419.6 1.06.952Q16.205 20 17 20");
}

</style>
