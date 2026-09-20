<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3zkfcbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:drive-folder-upload-outline-rounded" /></template>
<style>
.i3zkfcbff {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h4.31q.323 0 .628.13q.305.132.522.349L11.596 7h7.789q.69 0 1.153.463T21 8.616v8.769q0 .69-.462 1.153T19.385 19zm0-1h14.769q.269 0 .442-.173t.173-.442v-8.77q0-.269-.173-.442T19.385 8h-8.19L9.366 6.173q-.096-.096-.202-.134Q9.06 6 8.946 6h-4.33q-.269 0-.442.173T4 6.616v10.769q0 .269.173.442t.443.173M4 18V6zm8.357-1.912q.143-.144.143-.357v-4.2l1.766 1.765q.14.14.343.15t.364-.15t.16-.354t-.16-.354l-2.408-2.407q-.242-.243-.565-.243t-.566.243L9.066 12.55q-.141.14-.15.344t.15.364t.353.16t.354-.16L11.5 11.53v4.2q0 .213.143.357t.357.143t.357-.144");
}

</style>
