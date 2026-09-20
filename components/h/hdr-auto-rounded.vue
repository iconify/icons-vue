<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbj2ikb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hdr-auto-rounded" /></template>
<style>
.xbj2ikb-b {
  fill: currentColor;
  d: path("M9.8 14.2h4.4l.8 2.225q.1.275.325.425t.5.15q.475 0 .738-.387t.087-.813l-3.425-9.2q-.1-.275-.337-.437T12.35 6h-.7q-.3 0-.537.163t-.338.437L7.35 15.825q-.175.425.088.8t.737.375q.275 0 .5-.162T9 16.4zm.55-1.6l1.6-4.55h.1l1.6 4.55zM12 22q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22");
}

</style>
