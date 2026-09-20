<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p7kqj9bzq"/><path class="ydfmg1bnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lunc" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p7kqj9bzq {
  fill: var(--svg-color--ee7730, #ee7730);
  d: path("m20.86 10.51l-.723-.932l-4.123-2.651a5 5 0 0 0 .045.233a10 10 0 0 0 .203.758c.815 2.607 2.441 3.846 4.624 5.507a9 9 0 0 0 .027-2.678z");
}

.ydfmg1bnc {
  fill: var(--svg-color--f9d85e, #f9d85e);
  d: path("M12.864 14.247C8.945 12.495 6.496 8.94 6.353 5.36a.18.18 0 0 0-.3-.127a9.005 9.005 0 0 0-.801 12.714a9.016 9.016 0 0 0 15.18-2.742a.18.18 0 0 0-.21-.24a11.34 11.34 0 0 1-7.358-.719m8.049-3.497q-.318-.735-8.864-3.817c-4.3-1.552-5.1-3.049-1.986-3.726q.228-.05.459-.087c4.92-.802 9.559 2.53 10.362 7.44z");
}

</style>
