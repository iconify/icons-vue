<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq6mlhbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:file-map-stack-rounded" /></template>
<style>
.zq6mlhbhy {
  fill: currentColor;
  d: path("M8.116 17q-.691 0-1.153-.462T6.5 15.385V4.615q0-.69.463-1.153T8.116 3h10.769q.69 0 1.153.462t.462 1.153v10.77q0 .69-.462 1.152T18.884 17zm-3 3q-.691 0-1.153-.462T3.5 18.385V7.115q0-.213.143-.356T4 6.616t.357.143t.143.357v11.269q0 .23.192.423t.423.192h11.27q.213 0 .356.143t.144.357t-.144.357t-.356.143zm7.806-10.23q-.23-.23-.23-.578t.23-.578t.578-.23t.578.23t.23.578t-.23.578t-.578.23t-.578-.23m.578 4.268q1.621-1.379 2.426-2.572t.805-2.193q0-1.529-.972-2.42q-.972-.892-2.259-.892t-2.259.892t-.972 2.42q0 1 .805 2.193T13.5 14.04");
}

</style>
