<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bobm09brk"/><path class="n_8t9vgln"/><path class="hvs6ejb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:cross-browser-testing" /></template>
<style>
.bobm09brk {
  fill: var(--svg-color--50e4ea, #50E4EA);
  d: path("M7 7.013h242v242H7z");
}

.hvs6ejb5n {
  fill: var(--svg-color--05263a, #05263A);
  d: path("m178.169 167.75l4.254 16.126a174.369 174.369 0 0 1-47.14 35.914c-8.885-2.8-17.5-6.353-25.738-10.688c-4.846-2.53-9.584-5.277-14.16-8.292a167.542 167.542 0 0 1-11.389-8.184l94.173-24.876ZM63.374 84.023l24.849 94.146l-16.126 4.254a174.499 174.499 0 0 1-35.914-47.14c2.8-8.885 6.354-17.5 10.688-25.738a151.552 151.552 0 0 1 8.292-14.134c2.584-3.93 5.33-7.78 8.211-11.388ZM183.85 73.604a174.499 174.499 0 0 1 35.914 47.14a158.09 158.09 0 0 1-10.688 25.738a151.551 151.551 0 0 1-8.292 14.134c-2.584 3.93-5.33 7.78-8.184 11.415l-24.876-94.173l16.126-4.254Zm-63.158-37.367c8.884 2.8 17.499 6.38 25.737 10.688a161.613 161.613 0 0 1 14.134 8.292c3.958 2.557 7.78 5.33 11.415 8.184L77.804 88.277L73.551 72.15c13.541-14.565 29.506-26.707 47.14-35.914Z");
}

.n_8t9vgln {
  fill: var(--svg-color--05263a, #05263A);
  d: path("M242.512 13.46v229.08H13.461V13.46h229.051M255.973 0H0v256h256V0h-.027Z");
}

</style>
