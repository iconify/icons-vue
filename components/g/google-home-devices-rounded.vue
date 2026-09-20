<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqyy6bvvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:google-home-devices-rounded" /></template>
<style>
.iqyy6bvvf {
  fill: currentColor;
  d: path("M8.5 18H4.616q-.691 0-1.153-.462T3 16.384V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616V7.23h-1V5.616q0-.27-.173-.443T19.384 5H4.616q-.27 0-.443.173T4 5.616v10.769q0 .269.173.442t.443.173h6.769v3H9.308q-.343 0-.576-.232t-.232-.576zm7.27-3.23q.582-.581 1.422-.581t1.423.581t.581 1.422t-.582 1.423t-1.422.581t-1.422-.582t-.581-1.422q0-.84.581-1.422M20.161 9q.36 0 .6.244q.239.243.239.603v9.314q0 .36-.243.6q-.244.239-.604.239h-5.93q-.36 0-.599-.243t-.24-.604V9.84q0-.36.244-.6q.244-.239.604-.239zm-3.88 1.207q-.358.36-.358.911t.36.909t.912.358t.909-.36t.358-.912t-.36-.91t-.912-.357t-.91.36m3.015 8.092q.859-.856.859-2.103t-.856-2.105q-.856-.86-2.103-.86t-2.105.857q-.86.856-.86 2.103q0 1.246.857 2.105q.856.859 2.103.859q1.246 0 2.105-.856");
}

</style>
