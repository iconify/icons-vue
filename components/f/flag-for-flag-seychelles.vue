<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="e39cskb-j"/><path class="kah0d0b8l"/><path class="sm-nhrh9c"/><path class="pb63rpa_v"/><path class="shl33y2dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-seychelles" /></template>
<style>
.e39cskb-j {
  fill: var(--svg-color--d62828, #D62828);
  d: path("M32 5h-7.833L1.129 29.785l.001.001c.152.157.317.301.493.431l.001.001L36 13.667V9a4 4 0 0 0-4-4z");
}

.kah0d0b8l {
  fill: var(--svg-color--fcd856, #FCD856);
  d: path("M.763 29.35c.112.154.235.299.367.435L24.167 5H12L.763 29.35c-.001-.001-.001-.001 0 0z");
}

.pb63rpa_v {
  fill: var(--svg-color--eee, #EEE);
  d: path("M2.063 30.501l.004.002L36 22.333v-8.667L1.624 30.218c.14.103.287.198.439.283z");
}

.shl33y2dn {
  fill: var(--svg-color--007a3d, #007A3D);
  d: path("M4 31h28a4 4 0 0 0 4-4v-4.667L2.067 30.502A3.981 3.981 0 0 0 4 31z");
}

.sm-nhrh9c {
  fill: var(--svg-color--003f87, #003F87);
  d: path("M12 5H4a4 4 0 0 0-4 4v18c0 .878.283 1.689.762 2.349L12 5z");
}

</style>
