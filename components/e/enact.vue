<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":313};
const content = `<g class="jpallsb5j"><path class="vozx703bi"/><path class="hu4v-eb-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:enact" /></template>
<style>
.hu4v-eb-f {
  d: path("M128.052 312.21L256 219.665v-55.123l-128.052 83.591zm0-92.597l89.75-58.694V103l-89.854 52.329zm-.052-92.7l.104.052L256 55.072V0L127.948 62.577z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.jpallsb5j {
  fill: var(--svg-color--5582ff, #5582ff);
}

.vozx703bi {
  d: path("M127.948 248.133L50.31 197.409v-28.675l77.742 50.879l-.104-64.284l-77.638-45.238V83.28L128 126.913l.104.052l-.156-64.388L0 .052v219.51l128.052 92.648z");
}

</style>
