<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="j20j6bown"/><g class="dcew48b3c"><path class="rq3lekqfg"/><path class="stxfsgbib"/></g><g class="zyda5sbgr"><path class="ub_6knuik"/><path class="y8-t6jbnb"/></g><path class="qi0aklg4g"/><path class="hdz5g6b9e"/><path class="cwvyj7bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:closed-mailbox-with-raised-flag" /></template>
<style>
.cwvyj7bbo {
  fill: var(--svg-color--de374b, #de374b);
  d: path("M41.711 7.725c.008-.004.008-.03.016-.03h13.744c.061 0 .107.014.139.03l.005.004l.008.003c.029.018.054.044.054.078v7.44c0 .061-.091.115-.206.115h-7.485v22.602c0 .245-.04.461-.09.461h-6.169c-.053 0-.094-.215-.094-.461V7.813c0-.035.032-.063.078-.084");
}

.dcew48b3c {
  fill: var(--svg-color--a4806d, #a4806d);
}

.hdz5g6b9e {
  fill: var(--svg-color--7c9c9f, #7c9c9f);
  d: path("M25.378 13.174H13.05c-5.212 0-9.442 5.778-9.442 12.906v15.733h31.213V26.08c0-7.128-4.226-12.906-9.443-12.906");
}

.j20j6bown {
  fill: var(--svg-color--dfad92, #dfad92);
  d: path("M28.274 64H41.43c.111 0 .201-.289.201-.625V23.102c0-.338-.09-.625-.2-.625H28.273c-.06 0-.105.066-.138.168l-.002.02s-.003.002-.006.021a1.3 1.3 0 0 0-.053.416v40.273c0 .336.09.625.199.625");
}

.qi0aklg4g {
  fill: var(--svg-color--627c7f, #627c7f);
  d: path("M26.365 11.215H13.193c-5.57 0-10.087 6.175-10.087 13.79v16.808h33.341V25.004c0-7.614-4.515-13.789-10.086-13.789");
}

.rq3lekqfg {
  d: path("M34.229 64h7.294c.06 0 .11-.289.11-.625V23.102c0-.338-.05-.625-.11-.625H34.23c-.033 0-.057.066-.074.168l-.002.02s-.002.002-.005.021c-.018.09-.028.236-.028.416v40.273c0 .336.05.625.109.625");
}

.stxfsgbib {
  d: path("M28.274 46.626H41.43c.111 0 .201-.061.201-.134v-8.795c0-.074-.09-.138-.2-.138H28.273a.24.24 0 0 0-.133.037s0 .005-.007.005l-.008.006a.11.11 0 0 0-.051.09v8.795c0 .072.088.134.199.134");
}

.ub_6knuik {
  d: path("M24.504 11.215h-11.31c-5.57 0-10.088 6.175-10.088 13.79v16.808h11.311V25.004c0-7.614 4.515-13.789 10.087-13.789");
}

.y8-t6jbnb {
  d: path("M50.849 11.215H24.508c-5.572 0-10.087 6.174-10.087 13.79v16.808h46.514V25.004c0-7.614-4.513-13.789-10.083-13.789");
}

.zyda5sbgr {
  fill: var(--svg-color--7c9c9f, #7c9c9f);
}

</style>
