<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz4wc7bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keep-public-rounded" /></template>
<style>
.oz4wc7bbw {
  fill: currentColor;
  d: path("M4.942 15q-.22 0-.37-.153q-.149-.153-.149-.36v-.28q0-.098.037-.189q.036-.091.11-.164L6 12.423V5h-.5q-.213 0-.356-.144T5 4.499t.144-.356T5.5 4h4.464q.338 0 .485.304t-.03.592q-.392.723-.598 1.498T9.615 8q0 1.72.831 3.148t2.279 2.28q.275.134.463.363q.187.23.187.51t-.204.49q-.204.209-.479.209H9.5v4.927q0 .213-.144.356t-.357.144t-.356-.144t-.143-.356V15zm13.894-9.836Q20 6.33 20 8t-1.164 2.836T16 12t-2.835-1.164T12 8t1.165-2.835T16 4t2.836 1.165m-1.773 2.398q.437-.438.437-1.063t-.437-1.062T16 5t-1.062.438T14.5 6.5t.438 1.063T16 8t1.063-.437m.163 3.18q.582-.257 1.007-.745q.105-.123.068-.275q-.038-.154-.18-.235q-.493-.244-1.025-.366Q16.563 9 16.004 9t-1.092.122t-1.033.367q-.143.074-.18.226t.068.283q.425.489 1.006.745t1.226.257t1.227-.257");
}

</style>
