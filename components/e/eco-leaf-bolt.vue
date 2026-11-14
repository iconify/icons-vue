<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s56y9-bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eco-leaf-bolt" /></template>
<style>
.s56y9-bok {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.561 7.881q-4.137 4.728-3.306 12.202q.007.063.024.125q.018.061.046.119t.065.109t.083.097q.045.045.097.082q.053.036.111.064q.058.027.119.044q.062.017.125.023q7.968.797 12.543-3.778q4.665-4.666 4.281-13.501q-.003-.071-.02-.141q-.016-.07-.046-.135q-.029-.066-.071-.124q-.041-.059-.093-.109q-.052-.049-.113-.088q-.06-.039-.127-.066q-.066-.027-.137-.04q-.07-.014-.142-.014q-8.95 0-13.439 5.131m4.456.514q.604-.806 1.519-.385t.696 1.403l-.12.542q-.068.307.129.551q.196.245.509.245q1.004 0 1.453.898q.45.899-.153 1.702l-2.067 2.755q-.603.807-1.519.386t-.696-1.403l.12-.542q.068-.307-.129-.551q-.196-.245-.509-.245q-1.004 0-1.453-.898q-.45-.899.153-1.702z");
}

</style>
