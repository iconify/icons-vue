<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="s9u3yebnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:classification-28-regular" /></template>
<style>
.s9u3yebnj {
  fill: currentColor;
  d: path("M22.071 2a3.929 3.929 0 0 1 1.987 7.318l-5.105 2.992l2.952 2.952a3.75 3.75 0 0 1 0 5.303l-3.075 3.076a1.25 1.25 0 0 1-1.768 0l-.618-.618l-2.173 2.174a2.75 2.75 0 0 1-3.89 0L2.806 17.62a2.75 2.75 0 0 1 0-3.889l2.173-2.174l-.612-.613a1.25 1.25 0 0 1 0-1.767l3.075-3.075a3.75 3.75 0 0 1 5.304 0l2.944 2.944l2.993-5.104A3.93 3.93 0 0 1 22.072 2M3.865 14.792a1.25 1.25 0 0 0 0 1.768l7.577 7.577a1.25 1.25 0 0 0 1.769 0l2.173-2.174l-9.345-9.346zm7.819-7.63a2.25 2.25 0 0 0-3.182 0L5.603 10.06l12.342 12.343l2.9-2.898a2.25 2.25 0 0 0 0-3.183zM22.07 3.5a2.43 2.43 0 0 0-2.095 1.2l-3.19 5.442l1.071 1.072l5.443-3.19A2.43 2.43 0 0 0 22.07 3.5");
}

</style>
