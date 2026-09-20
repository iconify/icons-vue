<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doc-dkbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:carry-on-bag-checked-outline" /></template>
<style>
.doc-dkbzc {
  fill: currentColor;
  d: path("m16.608 19.712l3.357-3.358l-.557-.558l-2.8 2.8l-1.4-1.4l-.558.558zM9.5 19V9h-.885q-.269 0-.442.173T8 9.616v8.769q0 .269.173.442t.443.173zm2.277 1H8.616q-.691 0-1.153-.462T7 18.384V9.616q0-.691.463-1.153T8.616 8H14V4h-.615q-.422 0-.711-.29q-.29-.289-.29-.71H15v9.166q-.254.103-.518.236q-.265.133-.482.29V9h-3.5v10h.966q.055.273.128.512t.183.488m8.366-5.143q1.165 1.164 1.165 2.835t-1.165 2.836t-2.835 1.164t-2.836-1.164t-1.164-2.836q0-1.67 1.164-2.835q1.165-1.165 2.836-1.165t2.835 1.165M9.5 19V9zm1 0V9z");
}

</style>
