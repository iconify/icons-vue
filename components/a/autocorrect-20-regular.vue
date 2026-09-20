<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w2hoabbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:autocorrect-20-regular" /></template>
<style>
.w2hoabbfn {
  fill: currentColor;
  d: path("M9.144 5.484a1 1 0 0 1 1.712 0l2.127 3.517H12.5l-.067.004a3.75 3.75 0 1 0 2.366.996H17.5a.5.5 0 0 0 0-1h-3.348l-2.44-4.034c-.779-1.287-2.645-1.287-3.423 0L2.072 15.242a.5.5 0 0 0 .856.518zm3.106 4.517a2.75 2.75 0 1 1 0 5.5a2.75 2.75 0 0 1 0-5.5");
}

</style>
