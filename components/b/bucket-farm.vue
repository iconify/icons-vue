<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrp6pqb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bucket-farm" /></template>
<style>
.hrp6pqb6g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.428 4.157Q3.75 5.942 3.75 9q0 .062.01.123l1 6v.001l1 5.999q.011.065.033.128q.022.062.055.119q.032.058.075.109t.092.093q.051.043.108.076t.119.056t.127.034q.065.012.131.012h11q.066 0 .131-.012q.065-.011.127-.034t.119-.056t.108-.076t.092-.093q.043-.051.075-.109q.033-.057.055-.119q.022-.063.033-.128l2-12v-.004q.01-.059.01-.119q0-3.058-2.678-4.843Q15.274 2.625 12 2.625T6.428 4.157m-.111 11.185q1.611-1.003 3.223.25q2.728 2.122 5.186-.012q1.571-1.212 2.961-.264l-.822 4.934h-9.73zm11.636-1.62q-1.996-.999-4.163.686q-.018.013-.034.028q-1.534 1.342-3.296-.028q-2.202-1.713-4.405-.642l-.67-4.016h13.23zm.754-5.472H5.293Q5.791 4.125 12 4.125t6.707 4.125");
}

</style>
