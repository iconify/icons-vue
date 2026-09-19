<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ubq_58bja"/><path class="t42tkekqp"/><path class="nf734bc-l"/><g class="n1mjunbsu"><path class="w52bjd4-a"/><path class="s8svmcuhr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-libya" /></template>
<style>
.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.nf734bc-l {
  fill: var(--svg-color--128807, #128807);
  d: path("M0 43c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11v-3H0z");
}

.s8svmcuhr {
  d: path("m36.842 28.434l1.83 1.696l2.438-.54l-1.05 2.266l1.27 2.154l-2.483-.303l-1.657 1.872l-.48-2.449l-2.292-1l2.181-1.209z");
}

.t42tkekqp {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M54 10H10C3.373 10 0 14.925 0 21v3h64v-3c0-6.075-3.373-11-10-11");
}

.ubq_58bja {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M0 24h64v16H0z");
}

.w52bjd4-a {
  fill-rule: evenodd;
  d: path("M36.454 35.757c-1.49 2.328-4.595 3.794-7.845 2.845c-3.066-.898-5.173-3.87-4.999-7.07c.171-3.219 2.587-5.956 5.729-6.514c3.329-.592 6 1.195 7.144 3.062c-1.352-1.33-2.926-1.929-4.769-1.721c-1.445.165-2.651.821-3.594 1.92c-1.85 2.154-1.781 5.38.147 7.41c1.109 1.164 2.472 1.775 4.078 1.79c1.606.01 2.966-.597 4.109-1.719");
}

</style>
