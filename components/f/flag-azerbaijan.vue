<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="npzk8ibbi"/><path class="qyqkaubai"/><g class="n1mjunbsu"><path class="mvp-p_8ei"/><path class="tga_q034n"/></g><path class="pibytbbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-azerbaijan" /></template>
<style>
.mvp-p_8ei {
  d: path("M17.844 21.333a3.333 3.333 0 1 1 2.475-5.565a4 4 0 1 0 .001 4.464a3.33 3.33 0 0 1-2.476 1.101");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.npzk8ibbi {
  fill: var(--svg-color--e00034, #e00034);
  d: path("M0 13h36v10H0z");
}

.pibytbbie {
  fill: var(--svg-color--00ae65, #00ae65);
  d: path("M4 31h28a4 4 0 0 0 4-4v-4H0v4a4 4 0 0 0 4 4");
}

.qyqkaubai {
  fill: var(--svg-color--0098c3, #0098c3);
  d: path("M32 5H4a4 4 0 0 0-4 4v4h36V9a4 4 0 0 0-4-4");
}

.tga_q034n {
  d: path("m23.667 17.998l-1.196-.424l.544-1.146l-1.146.545l-.426-1.195l-.424 1.196l-.003-.002l-1.144-.542l.546 1.146l-1.196.426l1.196.424l-.544 1.146l1.141-.543l.005-.002l.426 1.195l.424-1.196l1.147.544l-.546-1.146z");
}

</style>
