<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juf8aby7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:devices-wearables-outline-rounded" /></template>
<style>
.juf8aby7g {
  fill: currentColor;
  d: path("M7 21V3zm5.588-14.913q.22-.22.22-.549t-.22-.549t-.55-.22t-.548.22t-.22.55t.22.548t.549.22t.549-.22M7.616 22q-.672 0-1.144-.472T6 20.385V3.615q0-.69.463-1.152T7.616 2h8.846q.67 0 1.143.472q.472.472.472 1.144v5.461q0 .214-.143.357t-.357.143t-.357-.143t-.143-.357V3.616q0-.27-.173-.443T16.462 3H7.616q-.27 0-.443.173T7 3.616v16.769q0 .269.173.442t.443.173h5.178q.25 0 .363.159q.112.158.112.341t-.122.341t-.372.159zm8.165-.673l-.221-1.435q-.727-.496-1.144-1.266T14 16.981t.416-1.646t1.143-1.266l.222-1.435q.055-.292.282-.482t.52-.19h1.834q.292 0 .52.19q.226.19.282.483l.221 1.434q.727.496 1.144 1.266T21 16.982t-.416 1.645t-1.144 1.266l-.22 1.435q-.057.292-.284.483q-.227.19-.519.19h-1.834q-.292 0-.52-.19q-.226-.19-.282-.483m3.494-2.571Q20 18.03 20 16.98t-.725-1.775t-1.775-.725t-1.775.725T15 16.98t.725 1.775t1.775.725t1.775-.725");
}

</style>
