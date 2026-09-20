<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyzn9l-nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:explore-nearby-sharp" /></template>
<style>
.tyzn9l-nx {
  fill: currentColor;
  d: path("M12.245 17.013q.114-.064.176-.192l.083-.192q.535-1.008 1.363-1.723q.829-.716 1.466-1.663q.319-.484.503-1.072q.183-.588.183-1.2q0-1.664-1.153-2.843T12.05 6.923q-1.617-.025-2.815 1.113q-1.198 1.139-1.25 2.779q-.035.681.139 1.29q.174.61.522 1.133q.637.947 1.487 1.652t1.359 1.736l.085.19q.064.13.181.195q.117.066.245.066t.242-.064m-1.436-4.88q-.501-.5-.501-1.19q0-.691.5-1.192Q11.31 9.25 12 9.25t1.191.501t.501 1.191t-.5 1.192q-.502.5-1.192.5t-1.191-.5M12.003 21q-1.866 0-3.51-.708q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709");
}

</style>
