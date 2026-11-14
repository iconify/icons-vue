<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1h1q_ope"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:home-energy" /></template>
<style>
.p1h1q_ope {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.935 9.143Q2.75 10.154 2.75 11.711v6.164q0 3.375 3.375 3.375h11.75q3.375 0 3.375-3.375v-6.164q0-1.557-1.185-2.568L14.19 4.132q-2.19-1.866-4.38 0zm7.14.84q.551-.736 1.388-.355q.838.381.644 1.281l-.061.282q-.046.216.093.388t.36.172q.929 0 1.353.826q.425.826-.115 1.581l-1.766 2.472q-.544.766-1.406.392q-.863-.374-.676-1.293l.081-.404q.044-.223-.1-.398t-.371-.176q-.927 0-1.342-.829q-.414-.829.142-1.571z");
}

</style>
