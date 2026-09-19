<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h5t4pjbby"/><path class="f-ix6p3pr"/><path class="g585fkfrz"/><path class="jbn779lei"/><path class="li9zuheoz"/><circle class="cpk0fnbgt"/><path class="bp4gphblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:crossword" /></template>
<style>
.bp4gphblg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.385 32.813l35.027 6.176M15.187 4.384L9.011 39.412M38.989 8.588l-6.176 35.027m10.803-28.428L8.588 9.011");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f-ix6p3pr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.885 15.173c2.127.3 1.518 2.109.55 2.109c-2.659 0-4.422-1.627-6.94-1.627c-3.414 0-4.132 4.922-1.2 5.617m6.565 3.224l1.693-1.694l1.694 1.694l-1.694 1.694zm1.693-1.692v-2.313m0 5.704v3.477");
}

.g585fkfrz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.876 26.272c-.805 1.94-2.123 3.813-6.005 3.813a4.68 4.68 0 0 1-4.74-4.94c0-2.786.686-4.063 2.768-5.404");
}

.h5t4pjbby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.885 15.173c4.472-.541 5.15 5.318.645 5.318c-1.972 0-5.636-1.705-7.14-1.705a1.396 1.396 0 0 0-1.095 2.477");
}

.jbn779lei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.999 27.717v-7.031l-4.568 1.932m1.609 6.349l2.959-1.25m-2.959-5.776v6.79");
}

.li9zuheoz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.876 26.272c.395 2.818-1.641 6.59-6.596 6.59c-3.85 0-7.203-2.727-7.203-6.563c0-3.986 3.281-5.777 5.822-6.559");
}

</style>
