<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5j0fib2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chart-dividers" /></template>
<style>
.h5j0fib2f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 5q0-2.75 2.75-2.75T14.75 5q0 1.66-1.002 2.318l4.959 13.931q.024.069.035.142t.007.147t-.022.145t-.05.139q-.031.067-.075.126t-.099.109t-.118.087q-.064.038-.134.063q-.069.024-.142.035t-.147.007t-.145-.022t-.139-.05q-.067-.031-.126-.075t-.109-.099t-.087-.118q-.038-.064-.063-.134l-4.986-14.01q-.149.009-.307.009t-.307-.009l-4.986 14.01q-.05.141-.15.252q-.1.11-.235.174t-.284.072t-.289-.042q-.07-.025-.134-.063q-.063-.038-.118-.087q-.055-.05-.099-.109t-.075-.126q-.032-.067-.05-.139q-.018-.071-.022-.145t.007-.147t.035-.142l4.959-13.931Q9.25 6.66 9.25 5");
}

</style>
