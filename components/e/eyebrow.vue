<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpd9yxrgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eyebrow" /></template>
<style>
.rpd9yxrgq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.397 5.364Q11.961.091 3.55 6.4q-.119.09-.195.218t-.097.276t.015.292t.127.264t.218.195t.276.097t.292-.015t.264-.127q7.589-5.691 15.153-.964q.126.079.273.104t.293-.009q.145-.034.266-.12q.122-.087.201-.214q.039-.062.065-.131t.039-.142t.01-.147t-.019-.146t-.047-.139t-.073-.127t-.097-.111q-.054-.051-.117-.09M2.443 14.498Q7.166 9.25 12 9.25t9.557 5.248q.047.051.083.11t.06.123t.037.132t.013.137t-.013.137q-.012.067-.037.132q-.024.064-.06.123t-.083.11Q16.834 20.75 12 20.75t-9.557-5.248q-.047-.051-.083-.11t-.06-.123t-.037-.132T2.25 15t.013-.137t.037-.132t.06-.123t.083-.11M12 12q-3 0-3 3t3 3t3-3t-3-3");
}

</style>
