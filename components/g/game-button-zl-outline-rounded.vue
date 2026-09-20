<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtudohzik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-button-zl-outline-rounded" /></template>
<style>
.xtudohzik {
  fill: currentColor;
  d: path("m8.117 14.289l3.187-4.595l.062-.436q0-.15-.101-.252q-.1-.102-.251-.102h-3.41q-.182 0-.298.115t-.116.296t.116.299t.298.117h2.704L7.12 14.337l-.061.435q0 .14.104.242q.103.102.242.102h3.64q.182 0 .298-.116t.116-.296t-.116-.298t-.298-.117zm5.86 0v-4.96q0-.173-.127-.3q-.127-.125-.302-.125t-.298.126t-.123.299v4.979q0 .343.232.575t.575.232h2.576q.181 0 .297-.115t.116-.296t-.116-.298t-.297-.118zM21 6.595v9.116q0 1.356-.977 2.322t-2.35.966H6.327q-1.372 0-2.35-.966T3 15.712V6.596q0-.666.475-1.14t1.14-.475h14.77q.666 0 1.14.474T21 6.596m-1.616-.615H4.616q-.27 0-.443.173T4 6.596v9.116q0 .96.684 1.624q.683.664 1.643.664h11.346q.96 0 1.644-.664q.683-.665.683-1.624V6.596q0-.269-.173-.442t-.442-.173m0 0H20H4z");
}

</style>
