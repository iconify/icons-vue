<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b84azyabi"/><path class="kpb-59boy"/><path class="x2bk3cxln"/><path class="my2gg1bbn"/><path class="nm0c_vb4u"/><path class="s_921kb2k"/><path class="lphxi9bdv"/><path class="b7ay8bb_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:balls-linear" /></template>
<style>
.b7ay8bb_n {
  d: path("M7.78713 14.9601C7.79713 14.6394 7.81052 12.4288 6.42893 9.80932C4.9338 6.97456 3.00065 5.92795 3.00065 5.92795L2.63281 5.70438");
}

.b84azyabi {
  d: path("M16.0201 8.07683C14.0016 8.27102 11.8566 8.87629 10.3665 10.3665C8.87629 11.8566 8.27102 14.0016 8.07683 16.0201M16.0201 8.07683C17.1891 7.96436 18.3157 7.9898 19.248 8.06108C20.7038 8.17239 21.8276 9.29618 21.9389 10.752C22.0102 11.6843 22.0356 12.8109 21.9232 13.9799M16.0201 8.07683L21.9232 13.9799M8.07683 16.0201C7.96436 17.1891 7.9898 18.3157 8.06108 19.248C8.17239 20.7038 9.29618 21.8276 10.752 21.9389C11.6843 22.0102 12.8109 22.0356 13.9799 21.9232C15.9984 21.729 18.1434 21.1237 19.6336 19.6336C21.1237 18.1434 21.729 15.9984 21.9232 13.9799M13.9799 21.9232L8.07683 16.0201");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kpb-59boy {
  d: path("M14.9939 8.21208C14.9499 7.2018 14.6688 6.18687 14.1282 5.25054C13.0651 3.40919 11.237 2.28489 9.27713 2.04733C7.92854 1.88387 6.51758 2.14025 5.25054 2.87177C2.14216 4.6664 1.07715 8.64107 2.87177 11.7495C4.01322 13.7265 6.03658 14.8769 8.15803 14.9907H8.21262");
}

.lphxi9bdv {
  d: path("M11.9219 9.21983C11.4735 8.68112 11.0043 8.01072 10.5718 7.19068C9.07667 4.35592 9.21845 2.04048 9.21845 2.04048");
}

.my2gg1bbn {
  d: path("M15.5 12.5L17.5 14.5");
}

.nm0c_vb4u {
  d: path("M12.5 15.5L14.5 17.5");
}

.s_921kb2k {
  d: path("M14 14L16 16");
}

.x2bk3cxln {
  d: path("M12.5 17.5L17.5 12.5");
}

</style>
