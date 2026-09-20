<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVGtK4giegH)" class="dak3fguih"/></g><defs><linearGradient id="SVGtK4giegH" x1="10.806" x2="15.402" y1="7.901" y2="9.483" gradientUnits="userSpaceOnUse"><stop class="ne3i2nbzg"/><stop offset=".51" class="mup0boi9a"/><stop offset="1" class="iiru55bfp"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:litt-background" /></template>
<style>
.dak3fguih {
  d: path("M10.88 7.695h2.277c.369-.041 1.058-.427.89-1.665c-.004-.033-.054-.05-.082-.02a2.6 2.6 0 0 1-.91.614c.04-.061.122-.27.122-.627c0-.353-.316-.78-.48-.948a1.13 1.13 0 0 1-.233-.992a.041.041 0 0 0-.062-.05a2.79 2.79 0 0 0-1.485 2.367a1.34 1.34 0 0 1-.373-.636c-.008-.04-.066-.053-.086-.016c-.357.574-.698 1.632.422 1.973m-.673.636v.594c0 .041.054.123.247.177c.192.049.307.303.316.422v2.584c0 .029-.025.078-.066.127a4 4 0 0 0-2.806 3.782C7.898 18.216 9.736 20 12 20s4.102-1.784 4.102-3.983a4 4 0 0 0-2.802-3.781c-.04-.05-.07-.099-.07-.132v-2.58c.009-.119.132-.369.32-.422c.193-.054.246-.14.246-.177v-.594a.224.224 0 0 0-.22-.226h-3.147a.22.22 0 0 0-.222.226m-1.6 7.198a1.81 1.81 0 0 1 1.847-1.444c.865 0 1.206.41 1.546.833c.353.435.714.874 1.653.874c.312-.005.62-.075.902-.205c.316-.185.76-.123.792.34v.09c0 1.817-1.518 3.29-3.384 3.29a3.34 3.34 0 0 1-3.233-2.36c-.14-.457-.18-.94-.118-1.414zm1.752 1.19a.82.82 0 1 0 0-1.642a.82.82 0 0 0 0 1.642m2.461.41a.41.41 0 1 0 0-.82a.41.41 0 0 0 0 .82");
}

.ft5dv1b6b {
  fill: none;
}

.iiru55bfp {
  stop-color: var(--svg-color--92e5eb, #92e5eb);
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.mup0boi9a {
  stop-color: var(--svg-color--47b6ca, #47b6ca);
}

.ne3i2nbzg {
  stop-color: var(--svg-color--33aac2, #33aac2);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
