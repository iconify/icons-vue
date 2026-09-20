<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ygb9m195p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:classification-28-filled" /></template>
<style>
.ygb9m195p {
  fill: currentColor;
  d: path("M22.072 2a3.93 3.93 0 0 1 1.986 7.318l-5.103 2.992l2.95 2.952a3.75 3.75 0 0 1 0 5.302l-3.075 3.077a1.25 1.25 0 0 1-1.767 0l-.617-.618l-2.174 2.174a2.75 2.75 0 0 1-3.889 0L2.806 17.62a2.75 2.75 0 0 1 0-3.889l2.173-2.174l-.612-.613a1.25 1.25 0 0 1 0-1.767L7.442 6.1a3.75 3.75 0 0 1 5.304 0l2.944 2.944l2.992-5.103A3.93 3.93 0 0 1 22.072 2M3.867 14.792a1.25 1.25 0 0 0 0 1.768l7.577 7.577a1.25 1.25 0 0 0 1.767 0l2.174-2.174l-9.344-9.345zM22.072 3.5a2.43 2.43 0 0 0-2.096 1.2l-3.19 5.442l1.072 1.07L23.3 8.025A2.43 2.43 0 0 0 22.072 3.5");
}

</style>
