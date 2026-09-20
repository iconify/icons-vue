<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g9lmgsurq"/><path class="lbrhxrnzz"/><path class="rnc1bbwyx"/><path class="rnle_7b3w"/><path class="ogetwgbyd"/><path class="t3839nunw"/><path class="dbd1q70iz"/><path class="rca9u-b8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-elasticbeanstalk" /></template>
<style>
.dbd1q70iz {
  fill: var(--svg-color--9d5025, #9d5025);
  d: path("m7.675 25.82l-1.767-.883v-5.369l1.767.374z");
}

.g9lmgsurq {
  fill: var(--svg-color--9d5025, #9d5025);
  d: path("M12.534 3.733V16h-1.427v11.553L16 30l2.956-14L16 2z");
}

.lbrhxrnzz {
  fill: var(--svg-color--f58536, #f58536);
  d: path("M16 2v28l3.466-1.733V16h1.427V4.447z");
}

.ogetwgbyd {
  fill: var(--svg-color--9d5025, #9d5025);
  d: path("m17.869 12.772l6.456-.714V6.18l-6.456 1.733z");
}

.rca9u-b8r {
  fill: var(--svg-color--f58536, #f58536);
  d: path("m14.131 19.228l-6.456.714v5.878l6.456-1.733z");
}

.rnc1bbwyx {
  fill: var(--svg-color--6b3a19, #6b3a19);
  d: path("m26.092 12.432l-6.184.578l-2.039-.238l6.456-6.592z");
}

.rnle_7b3w {
  fill: var(--svg-color--f58536, #f58536);
  d: path("m24.325 6.18l1.767.883v5.369l-1.767-.374z");
}

.t3839nunw {
  fill: var(--svg-color--fbbf93, #fbbf93);
  d: path("m5.908 19.568l6.184-.578l2.039.238l-6.456 6.592z");
}

</style>
