<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb4o__b5r"/><path clip-rule="evenodd" class="n2zpnybfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:double-alt-arrow-left-bold-duotone" /></template>
<style>
.n2zpnybfq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.4881 19.5695C13.8026 19.2999 13.839 18.8264 13.5694 18.5119L7.98781 12L13.5694 5.48811C13.839 5.17361 13.8026 4.70014 13.4881 4.43057C13.1736 4.161 12.7001 4.19743 12.4306 4.51192L6.43056 11.5119C6.18981 11.7928 6.18981 12.2072 6.43056 12.4881L12.4306 19.4881C12.7001 19.8026 13.1736 19.839 13.4881 19.5695Z");
}

.rb4o__b5r {
  fill: currentColor;
  d: path("M17.75 19C17.75 19.3138 17.5546 19.5945 17.2602 19.7034C16.9658 19.8123 16.6348 19.7264 16.4306 19.4881L10.4306 12.4881C10.1898 12.2072 10.1898 11.7927 10.4306 11.5119L16.4306 4.51188C16.6348 4.27358 16.9658 4.18767 17.2602 4.29656C17.5546 4.40545 17.75 4.68612 17.75 4.99997L17.75 19Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
