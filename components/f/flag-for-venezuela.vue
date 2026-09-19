<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bpn-oncsg"/><path class="pk07sfbhl"/><path class="u7es78bok"/><path class="kmhnvub0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-venezuela" /></template>
<style>
.bpn-oncsg {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("M32 2C18.9 2 7.8 10.4 3.7 22h56.6C56.2 10.4 45.1 2 32 2");
}

.kmhnvub0y {
  fill: var(--svg-color--fff, #fff);
  d: path("m34.6 27.1l1 1.1l-.2-1.5l1.3-.6l-1.4-.3l-.2-1.4l-.7 1.3l-1.5-.3l1 1.1l-.7 1.3zm-5.4.1l1.3.6l-.7-1.3l1-1.1l-1.5.3l-.7-1.3l-.2 1.5l-1.5.2l1.4.7l-.1 1.4zm-5 1.8l1.5.2l-1.2-1l.5-1.3l-1.3.7l-1.2-1l.5 1.5l-1.3.7l1.5.1l.4 1.5zm-4 3.5l1.5-.4l-1.5-.5v-1.5l-.9 1.2l-1.5-.5l.9 1.2l-.8 1.1l1.4-.4l1 1.2zM17.9 37l1.2-.9l-1.6.1l-.5-1.4l-.4 1.4H15l1.3.8l-.4 1.4l1.2-.9l1.4.8zm28.2-.2l-.5 1.4l1.3-.9l1.2.9l-.4-1.4L49 36h-1.6l-.4-1.3l-.5 1.3h-1.6zm-2.5-4.5l.1 1.4l.9-1.1l1.4.3l-.9-1.1l.9-1.2l-1.4.5l-1-1.1v1.4l-1.4.5zm-4-3.4l.6 1.4l.4-1.5l1.5-.1l-1.3-.7l.4-1.5l-1.2 1l-1.3-.7l.6 1.3l-1.2 1z");
}

.pk07sfbhl {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 62c13.1 0 24.2-8.3 28.3-20H3.7C7.8 53.7 18.9 62 32 62");
}

.u7es78bok {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M3.7 22C2.6 25.1 2 28.5 2 32s.6 6.9 1.7 10h56.6c1.1-3.1 1.7-6.5 1.7-10s-.6-6.9-1.7-10z");
}

</style>
