<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="lmx84zeuz"/><path class="ci03thb0u"/><path class="v-dqmfzut"/><path class="mt5gidrvy"/><path class="wsdrx7erd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:computer-disk" /></template>
<style>
.ci03thb0u {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M34 18c0 8.837-7.163 16-16 16S2 26.837 2 18S9.164 2 18 2s16 7.164 16 16m-16-2.667a2.667 2.667 0 1 0 0 5.334a2.667 2.667 0 0 0 0-5.334");
}

.lmx84zeuz {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.mt5gidrvy {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("m18.469 22.189l1.111 9.941a14.18 14.18 0 0 0 8.476-4.074l-7.062-7.062a4.2 4.2 0 0 1-2.525 1.195m-.91-8.38l-1.048-9.953a14.2 14.2 0 0 0-8.569 4.087l7.062 7.062a4.2 4.2 0 0 1 2.555-1.196");
}

.v-dqmfzut {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M13.811 17.535a4.2 4.2 0 0 1 1.193-2.53L7.943 7.943a14.18 14.18 0 0 0-4.075 8.487zm8.378.93a4.22 4.22 0 0 1-1.194 2.53l7.062 7.062a14.18 14.18 0 0 0 4.075-8.487z");
}

.wsdrx7erd {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M36 21a2 2 0 0 1-2 2H23a2 2 0 0 1-2-2v-6a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2z");
}

</style>
