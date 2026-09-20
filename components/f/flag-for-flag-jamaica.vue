<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tp7_cib5j"/><path class="iwu3yobal"/><path class="kr681db7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-jamaica" /></template>
<style>
.iwu3yobal {
  fill: var(--svg-color--141414, #141414);
  d: path("M35.762 28.361c.154-.425.238-.883.238-1.361V9c0-.477-.084-.935-.237-1.359l-.001-.002L21.416 18zM14.584 18L.238 7.639v.001A4 4 0 0 0 0 9v18c0 .478.084.936.238 1.361z");
}

.kr681db7s {
  fill: var(--svg-color--ffd202, #ffd202);
  d: path("M32.535 5.035L18 15.533L3.465 5.035h-.001A4.01 4.01 0 0 0 .237 7.638L14.584 18L.238 28.361l.001.003a4 4 0 0 0 3.223 2.6h.004L18 20.467l14.534 10.497a4 4 0 0 0 3.227-2.601l.001-.003L21.416 18L35.762 7.639a4 4 0 0 0-3.227-2.604");
}

.tp7_cib5j {
  fill: var(--svg-color--009b3a, #009b3a);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

</style>
