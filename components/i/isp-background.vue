<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="p8hac_gon"/><path class="gc68wlb1q"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:isp-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gc68wlb1q {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.669 9.715c.284-.44.453-.944.489-1.466c0-1.791-1.76-3.125-3.485-3.138c-1.222-.009-2.453.52-3.07 1.618l-2.49 4.36c-.16.24-.261.513-.297.8c-.013.542.298 1.066.747 1.444l3.377-5.929c.471-.844 1.725-1.16 2.578-.729c.92.445 1.289 1.534.782 2.391L10.678 15.4c-.293.547.173 1.054.715 1.045c.28 0 .547-.12.685-.37zM8.29 14.284a3 3 0 0 0-.435 1.467c0 1.79 1.733 3.12 3.466 3.137c1.232.013 2.414-.52 3.036-1.618l2.515-4.413c.151-.27.325-.564.325-.857c0-.52-.294-.983-.742-1.334l-3.44 5.956c-.334.6-1.005.88-1.69.88c-.977-.005-1.924-.627-1.915-1.707c0-.276.094-.578.245-.836l3.693-6.337c.275-.507-.142-1.049-.675-1.067a.8.8 0 0 0-.725.391l-3.662 6.338zm8.604-4.649a2.8 2.8 0 0 1 .978 3.716l-2.515 4.413a4.59 4.59 0 0 1-4.031 2.235c-2.862-.022-5.422-2.902-4.213-5.777c-1.258-.831-1.707-2.356-.978-3.627l2.489-4.36C9.438 4.813 11.05 4 12.674 4c2.862 0 5.332 2.751 4.226 5.635z");
}

.p8hac_gon {
  fill: var(--svg-color--3337d6, #3337d6);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
