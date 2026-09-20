<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al6ns_-ew"/><path class="mh09cdv5z"/><path class="def4l2f3v"/><path class="p-b676fqt"/><path class="noneekcnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:autonomys" /></template>
<style>
.al6ns_-ew {
  d: path("m14.268 3l6.393 11.35A9.3 9.3 0 0 0 21 11.853c0-4.254-2.86-7.83-6.732-8.853");
}

.def4l2f3v {
  d: path("M12 21c2.536 0 4.825-1.067 6.462-2.78H5.538A8.9 8.9 0 0 0 12 21m-9-9.146c0 .866.12 1.704.34 2.498L9.732 3C5.86 4.022 3 7.599 3 11.854");
}

.mh09cdv5z {
  d: path("m14.268 3l6.393 11.35A9.3 9.3 0 0 0 21 11.853c0-4.254-2.86-7.83-6.732-8.853M12 21c2.536 0 4.825-1.067 6.462-2.78H5.538A8.9 8.9 0 0 0 12 21");
}

.noneekcnk {
  d: path("M16.277 14.336L12 6.742l-4.276 7.594z");
}

.p-b676fqt {
  d: path("M3 11.854c0 .866.12 1.704.34 2.498L9.732 3C5.86 4.022 3 7.599 3 11.854m13.277 2.482L12 6.742l-4.276 7.594z");
}

</style>
