<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwhkambtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:frame-person-outline" /></template>
<style>
.gwhkambtt {
  fill: currentColor;
  d: path("M12 11.885q-1.044 0-1.772-.728T9.5 9.385q0-1.02.728-1.76T12 6.885q1.02 0 1.76.74t.74 1.76q0 1.044-.74 1.772t-1.76.728m0-1q.617 0 1.059-.432t.441-1.068q0-.618-.441-1.059q-.442-.441-1.059-.441q-.637 0-1.068.441T10.5 9.385q0 .636.432 1.068q.431.432 1.068.432m-5.5 6.23v-1.4q0-.41.205-.756q.204-.347.558-.565q1.074-.636 2.278-.958q1.205-.32 2.459-.32t2.459.32t2.278.958q.354.217.558.565q.205.347.205.757v1.4zm3.25-2.673q-1.129.327-2.215.943v.75h8.93v-.77q-1.067-.615-2.206-.932q-1.138-.317-2.259-.317t-2.25.326m4.51 1.693h2.205h-8.93zM4.615 21q-.691 0-1.153-.462T3 19.385V16h1v3.385q0 .23.192.423t.423.192H8v1zM3 8V4.616q0-.691.463-1.153T4.615 3H8v1H4.616q-.231 0-.424.192T4 4.615V8zm13 13v-1h3.385q.23 0 .423-.192t.192-.424V16h1v3.385q0 .69-.462 1.152T19.385 21zm4-13V4.616q0-.231-.192-.424T19.385 4H16V3h3.385q.69 0 1.152.463T21 4.615V8z");
}

</style>
