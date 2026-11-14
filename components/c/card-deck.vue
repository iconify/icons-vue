<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqwzxs61q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:card-deck" /></template>
<style>
.xqwzxs61q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.25 16.75v.5q0 2.25-2.25 2.25h-.782q-.296 2.75-3.343 2.75h-5.25q-3.375 0-3.375-3.375v-8.75q0-3.182 3-3.364V6.25Q6.25 4 8.5 4h.75v-.5q0-2.25 2.25-2.25H19q2.25 0 2.25 2.25v11q0 2.25-2.25 2.25zM10.75 4v-.5q0-.75.75-.75H19q.75 0 .75.75v11q0 .75-.75.75h-.75v-9Q18.25 4 16 4zM16 5.5H8.5q-.75 0-.75.75v.5h4.125q3.375 0 3.375 3.375V18H16q.75 0 .75-.75v-11q0-.75-.75-.75m-4.994 6.844q-.616-.959-1.756-.959t-1.756.959l-.604.94q-.782 1.216 0 2.433l.604.938q.616.96 1.756.96t1.756-.959l.604-.94q.782-1.216 0-2.433l-.604-.938z");
}

</style>
