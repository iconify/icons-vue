<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="plg8wwb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-repeat-all-32-regular" /></template>
<style>
.plg8wwb4h {
  fill: currentColor;
  d: path("M26.611 10.286c.388-.387 1.021-.393 1.367.032A9 9 0 0 1 21 25h-9.586l3.293 3.293a1 1 0 0 1-1.414 1.414l-5-5a1 1 0 0 1 0-1.414l5-5a1 1 0 1 1 1.414 1.414L11.414 23H21a7 7 0 0 0 5.565-11.245c-.337-.442-.347-1.076.046-1.469m-9.318-7.993a1 1 0 0 1 1.414 0l5 5a1 1 0 0 1 0 1.414l-5 5a1 1 0 1 1-1.414-1.414L20.586 9H11a7 7 0 0 0-5.566 11.244c.337.441.347 1.075-.045 1.468c-.388.388-1.022.394-1.368-.031A9 9 0 0 1 11 7h9.585l-3.293-3.294a1 1 0 0 1 0-1.414");
}

</style>
