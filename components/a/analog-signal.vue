<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgz_9abkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:analog-signal" /></template>
<style>
.tgz_9abkl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.788 11.763q2.046-6.138 5.087-6.138q2.978 0 5.805 6.058q2.423 5.192 4.445 5.192q1.959 0 3.663-5.112q.048-.142.145-.254q.098-.113.232-.18q.133-.067.282-.077q.149-.011.29.036q.07.024.134.06q.065.037.12.085q.056.049.101.107q.046.059.079.125t.052.137q.02.071.025.145t-.004.147t-.032.143q-2.046 6.138-5.087 6.138q-2.978 0-5.805-6.058q-2.423-5.192-4.445-5.192q-1.959 0-3.663 5.112q-.048.142-.145.254q-.098.113-.232.18q-.133.067-.282.077q-.149.011-.29-.036q-.07-.024-.134-.06q-.065-.037-.12-.085q-.056-.049-.101-.107q-.046-.059-.079-.125t-.052-.137t-.025-.145t.004-.147t.032-.143");
}

</style>
