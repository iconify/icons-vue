<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpgxh6d_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:blender-outline-sharp" /></template>
<style>
.lpgxh6d_k {
  fill: currentColor;
  d: path("M6.808 21v-3.75l1.927-1.639l-.76-4.919H4.769V4H10v-.77h4V4h3.052l-1.786 11.612l1.926 1.638V21zm1.02-11.308L7.095 5H5.77v4.692zm4.721 8.857q.22-.22.22-.549t-.22-.549t-.549-.22t-.549.22t-.22.549t.22.549t.549.22t.549-.22M9.662 15h4.677L15.88 5H8.119zm-1.854 5h8.384v-2.308L14.187 16H9.814l-2.006 1.692zM12 18");
}

</style>
