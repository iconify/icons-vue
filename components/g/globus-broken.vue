<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kmybgh8wb"/><path class="kk05o5b_l"/><path class="zhgqgje4f"/><path class="ek8qykb_o"/><path class="o9a0il3ys"/><path class="mnp2t7kvq"/><path class="k3g5je5gb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:globus-broken" /></template>
<style>
.ek8qykb_o {
  d: path("M14 22H12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k3g5je5gb {
  d: path("M18.8194 11.5869C18.5711 12.312 18.0284 13.2563 16.1455 13.276C16.1455 13.276 13.9497 13.276 13.291 14.5174C12.8053 15.4326 13.0283 16.4182 13.2382 16.891");
}

.kk05o5b_l {
  d: path("M12 22V20");
}

.kmybgh8wb {
  d: path("M4 16.5623C5.88838 18.6722 8.63263 20 11.687 20C15.8429 20 19.4247 17.5418 21.0576 14M18.5623 2C20.6722 3.88838 22 6.63263 22 9.68699");
}

.mnp2t7kvq {
  d: path("M7.27539 4.83583C7.89969 5.5266 8.81082 6.84087 8.93179 8.23714C9.06307 9.75237 10.0275 10.9836 11.5007 11.0003C12.0668 11.0067 12.6394 10.5825 12.638 9.99537C12.6375 9.8138 12.6086 9.62816 12.5634 9.45737C12.5005 9.21982 12.4949 8.94653 12.6257 8.66696C13.0831 7.68895 13.9827 7.42624 14.6956 6.89509C15.0117 6.65952 15.3001 6.41102 15.4273 6.21085C15.7308 5.73317 16.0343 4.8426 15.9977 4.25293");
}

.o9a0il3ys {
  d: path("M5.93648 13.5C5.34088 12.4704 5 11.275 5 10C5 6.13401 8.13401 3 12 3C15.866 3 19 6.13401 19 10C19 13.866 15.866 17 12 17C10.725 17 9.52961 16.6591 8.5 16.0635");
}

.zhgqgje4f {
  d: path("M12 22H10");
}

</style>
