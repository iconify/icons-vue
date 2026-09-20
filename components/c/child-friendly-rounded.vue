<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th2_b1b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:child-friendly-rounded" /></template>
<style>
.th2_b1b5i {
  fill: currentColor;
  d: path("M8.32 19.916Q8 19.601 8 19.12t.315-.8t.796-.32t.8.315t.32.796t-.315.8t-.796.32t-.8-.315m8.46 0q-.319-.315-.319-.796t.315-.8t.797-.32q.48 0 .8.315t.32.796t-.316.8t-.795.32t-.801-.315M12.769 8.254L9.64 4.477q.823-.315 1.661-.454t1.73-.138q.853 0 1.6.157t1.406.475q.225.14.275.392q.05.25-.167.418zM3.576 6.462q-.213 0-.356-.144t-.143-.356q0-1.018.73-1.76q.731-.74 1.785-.74q.692 0 1.24.378q.549.38 1.218 1.187l8.892 10.708q.33.384.115.825t-.71.44H12q-1.671 0-2.835-1.164Q8 14.67 8 13V6.492l-.692-.83q-.542-.675-.943-.938t-.811-.262q-.633 0-1.055.43t-.422 1.07q0 .212-.144.356t-.357.144");
}

</style>
