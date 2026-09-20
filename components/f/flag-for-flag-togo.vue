<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="pwxxvcbnh"/><path class="rj-ftd_ep"/><path class="mwo_6ecfh"/><path class="qiuyinsdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-togo" /></template>
<style>
.mwo_6ecfh {
  fill: var(--svg-color--d21034, #d21034);
  d: path("M4 5C1.879 5 .161 6.656.026 8.743V20.5h15.5V5z");
}

.pwxxvcbnh {
  fill: var(--svg-color--006a4e, #006a4e);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-1.2H0zm15.526-6.5H15.5l20.5.1v-5.2H15.526zM32 5H15.526v5.2H36V9a4 4 0 0 0-4-4");
}

.qiuyinsdb {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.339 11.413H8.885l-.013-.04L7.776 8l-.022.068l-1.087 3.345H3.078l2.858 2.077l.045.033l-1.067 3.285l-.042.129l2.904-2.11l2.903 2.11l-1.109-3.414l2.904-2.11z");
}

.rj-ftd_ep {
  fill: var(--svg-color--ffce00, #ffce00);
  d: path("M15.526 15.333v.067H36v-5.2H15.526zM.026 20.5L0 25.8h36v-5.2l-20.5-.1z");
}

</style>
