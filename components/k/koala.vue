<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="xjc5ecb2l"/><path class="qkz1ebd3q"/><path class="q2wwqhbcu"/><circle class="dpu51accs"/><circle class="uspnwhbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:koala" /></template>
<style>
.dpu51accs {
  cx: 12.5px;
  cy: 19.875px;
  r: 1.5px;
  fill: var(--svg-color--292f33, #292f33);
}

.q2wwqhbcu {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M21.728 24.807C21.728 28.152 20 29 18 29s-3.727-.848-3.727-4.193S16 18.75 18 18.75s3.728 2.712 3.728 6.057");
}

.qkz1ebd3q {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M9.554 9.854A9 9 0 0 0 8.6 9.8C5.507 9.8 3 11.293 3 15.026c0 2.154.838 3.808 2.138 4.824c.473-3.797 2.005-7.416 4.416-9.996M27.4 9.8c-.317 0-.637.021-.955.054c2.412 2.58 3.943 6.199 4.416 9.997C32.162 18.834 33 17.181 33 15.026c0-3.733-2.507-5.226-5.6-5.226");
}

.uspnwhbvd {
  cx: 23.5px;
  cy: 19.875px;
  r: 1.5px;
  fill: var(--svg-color--292f33, #292f33);
}

.xjc5ecb2l {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M36 13.533C36 8.867 32.866 7 29 7c-1.621 0-3.285.354-4.676 1.027C22.523 6.798 20.405 6.062 18 6.062s-4.523.736-6.324 1.965C10.285 7.354 8.621 7 7 7c-3.866 0-7 1.867-7 6.533c0 3.844 2.128 6.417 5.038 7.206a20 20 0 0 0-.068 1.611c0 5.729 4.52 7.675 8.581 8.326C14.649 31.487 16.232 32 18 32s3.351-.513 4.449-1.323c4.062-.651 8.581-2.597 8.581-8.326q-.002-.807-.068-1.611c2.91-.79 5.038-3.363 5.038-7.207");
}

</style>
