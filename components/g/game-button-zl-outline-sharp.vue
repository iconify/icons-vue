<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twknbr7xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-button-zl-outline-sharp" /></template>
<style>
.twknbr7xh {
  fill: currentColor;
  d: path("M7.06 15.116h4.4v-.827H8.117l3.249-4.681v-.704H7.19v.827h3.117L7.06 14.423zM21 5v10.73q0 1.368-.973 2.329q-.973.96-2.354.96H6.327q-1.406 0-2.366-.96Q3 17.098 3 15.73V5zm-1 1H4v9.73q0 .947.671 1.618t1.656.671h11.346q.96 0 1.643-.671q.684-.671.684-1.617zm0 0H4zm-6.873 9.116h3.796v-.827h-2.946V8.904h-.85z");
}

</style>
