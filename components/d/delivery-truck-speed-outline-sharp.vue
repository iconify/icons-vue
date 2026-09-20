<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhj3l8bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:delivery-truck-speed-outline-sharp" /></template>
<style>
.rhj3l8bjj {
  fill: currentColor;
  d: path("M5.73 18.27Q5 17.537 5 16.5H2.77l.218-1h2.268q.271-.667.875-1.084Q6.735 14 7.5 14t1.37.416q.603.417.874 1.084h4.618L16.558 6H5.608l.023-.098q.073-.392.38-.647T6.735 5h11.073l-.81 3.5h2.079l2.712 3.616l-.866 4.384h-1.154q0 1.039-.73 1.77t-1.77.73t-1.769-.73t-.73-1.77H10q0 1.039-.73 1.77T7.5 19t-1.77-.73m10.157-5.02h4.652l.177-.89l-2.139-2.86h-1.818zm.429-6.248L16.558 6l-2.197 9.5l.243-1.002l.792-3.496zM1.672 12.998l.25-1h4.48l-.25 1zm2-3.496l.25-1h5.48l-.25 1zM7.5 18q.617 0 1.059-.441Q9 17.117 9 16.5t-.441-1.059T7.5 15t-1.059.441Q6 15.883 6 16.5t.441 1.059Q6.883 18 7.5 18m9.77 0q.617 0 1.058-.441q.441-.442.441-1.059t-.441-1.059T17.269 15t-1.058.441q-.442.442-.442 1.059t.441 1.059q.442.441 1.06.441");
}

</style>
