<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njxwicy6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:loyalty-sharp" /></template>
<style>
.njxwicy6u {
  fill: currentColor;
  d: path("m13 16.923l3.039-3.154q.217-.217.331-.506q.114-.288.114-.636q0-.639-.453-1.114q-.454-.475-1.096-.475q-.489 0-.964.256T13 12.2q-.52-.661-.982-.911t-.953-.25q-.642 0-1.096.475q-.453.475-.453 1.113q0 .348.114.637q.114.288.331.505zm-.002 4.748L3 11.692V3h8.692l9.993 10.004zM6.55 7.558q.421 0 .715-.292t.293-.708q0-.425-.292-.722t-.708-.297q-.425 0-.722.295t-.297.716t.295.715t.716.293");
}

</style>
