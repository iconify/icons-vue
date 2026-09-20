<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="xcfhw0bzy"/><path class="e7fptkbdf"/><path class="ubzow7blw"/><circle transform="rotate(-76.714 13.001 18.001)" class="ted839byk"/><circle class="qz5f_4b7j"/><g class="if5gbshjf"><path class="jzdr2ac-l"/><path class="dry7r5bzn"/><path class="uldexubqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-new-caledonia" /></template>
<style>
.dry7r5bzn {
  d: path("M14.25 14.719a1.22 1.22 0 1 1-2.439 0a1.22 1.22 0 0 1 2.439 0m-.219 7.547c0 .786-.448 1.422-1 1.422s-1-.636-1-1.422s.448-1.422 1-1.422s1 .635 1 1.422m.219-3.985c0 .406-.546.734-1.219.734s-1.219-.328-1.219-.734s.546-.734 1.219-.734s1.219.328 1.219.734M11.688 13s-.125-.875.125-1.25s.906-.719 1.438-.844C13.781 10.781 14.5 10 14.5 10s-.094 1.156-.969 1.875S11.688 13 11.688 13m-.766 1.776s.484.312.609.781s.469.969 1.469.969v.562s-.844.062-1.312-.125c-.469-.188-.594-1.062-.594-1.375s-.172-.812-.172-.812m4.187 0s-.484.312-.609.781s-.469.969-1.469.969v.562s.844.062 1.312-.125c.469-.188.594-1.062.594-1.375s.172-.812.172-.812");
}

.e7fptkbdf {
  fill: var(--svg-color--ed4135, #ed4135);
  d: path("M0 13h36v10H0z");
}

.if5gbshjf {
  fill: var(--svg-color--141414, #141414);
}

.jzdr2ac-l {
  d: path("M12.87 9.008h.322v17.984h-.322z");
}

.qz5f_4b7j {
  cx: 13px;
  cy: 18px;
  r: 9px;
  fill: var(--svg-color--fae600, #fae600);
}

.ted839byk {
  cx: 13px;
  cy: 18px;
  r: 9.402px;
  fill: var(--svg-color--141414, #141414);
}

.ubzow7blw {
  fill: var(--svg-color--0035ad, #0035ad);
  d: path("M32 5H4a4 4 0 0 0-4 4v4h36V9a4 4 0 0 0-4-4");
}

.uldexubqa {
  d: path("M14.938 21.188c0-.312-.141-1.188-.609-1.375c-.47-.188-1.329-.26-1.329-.26s-.844.072-1.312.26s-.594 1.062-.594 1.375S10.922 23 10.922 23s.656-1.098.781-1.566c.125-.469.641-1.053 1.297-1.053c.672 0 1.203.562 1.328 1.031S15.102 23 15.102 23s-.164-1.5-.164-1.812M13 24v3s-.875.094-2.125-.234s-1.484-.453-1.484-.453s1.272-1.273 1.828-1.75C11.875 24 13 24 13 24m0 0v3s.875.094 2.125-.234s1.484-.453 1.484-.453s-1.273-1.273-1.828-1.75C14.125 24 13 24 13 24");
}

.xcfhw0bzy {
  fill: var(--svg-color--009543, #009543);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
