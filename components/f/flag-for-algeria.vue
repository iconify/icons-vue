<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hj_zgnw6y"/><path class="n7qrwqb6f"/><g class="iwmpeujjh"><path class="yea_klbfx"/><path class="dg1c5hbem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-algeria" /></template>
<style>
.dg1c5hbem {
  d: path("m36.726 26.14l1.74 3.578l3.924.592l-2.863 2.76l.643 3.919l-3.503-1.869l-3.537 1.828l.702-3.908L31 30.24l3.937-.548z");
}

.hj_zgnw6y {
  fill: var(--svg-color--137a08, #137a08);
  d: path("M61 43c0 6.075-3.373 11-10 11H10C3.373 54 0 49.075 0 43V21c0-6.075 3.373-11 10-11h41c6.627 0 10 4.925 10 11z");
}

.iwmpeujjh {
  fill: var(--svg-color--ec1c24, #ec1c24);
}

.n7qrwqb6f {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M54 10H32v44h22c6.627 0 10-4.925 10-11V21c0-6.075-3.373-11-10-11");
}

.yea_klbfx {
  fill-rule: evenodd;
  d: path("M43.45 39.14c-2.729 4.254-8.409 6.94-14.359 5.202c-5.608-1.644-9.463-7.08-9.143-12.941c.312-5.888 4.732-10.896 10.48-11.917c6.094-1.083 10.985 2.185 13.07 5.601c-2.476-2.434-5.354-3.528-8.726-3.146c-2.643.303-4.85 1.498-6.577 3.512c-3.382 3.939-3.259 9.844.274 13.562c2.025 2.128 4.517 3.245 7.458 3.271c2.941.021 5.432-1.091 7.521-3.144");
}

</style>
