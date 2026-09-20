<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvko0mb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:clock-arrow-down-outline-rounded" /></template>
<style>
.fvko0mb0t {
  fill: currentColor;
  d: path("M4.207 16.441q-1.86-1.867-1.86-4.534T4.208 7.37T8.733 5.5t4.532 1.867t1.87 4.534q0 2.666-1.867 4.537t-4.534 1.87t-4.527-1.867m8.355-.706q1.573-1.572 1.573-3.833q0-2.26-1.573-3.83Q10.99 6.5 8.73 6.5T4.908 8.073q-1.562 1.572-1.562 3.832t1.562 3.832q1.561 1.57 3.822 1.57t3.832-1.572M9.25 11.733v-3.04q0-.213-.144-.357t-.357-.144t-.356.144t-.143.356v3.171q0 .154.056.297t.186.274l2.192 2.193q.16.16.355.15t.353-.16t.16-.354t-.16-.363zm9.57 6.702l-2.012-2.012q-.16-.165-.16-.357t.166-.35q.165-.16.356-.163q.192-.003.351.163l1.364 1.363V5.5q0-.213.143-.356T19.385 5t.356.144t.144.356v11.585l1.369-1.37q.16-.16.354-.16t.353.16t.16.354t-.16.354l-2.011 2.012q-.242.242-.565.242t-.566-.242");
}

</style>
