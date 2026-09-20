<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju98ztb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:decimal-decrease-rounded" /></template>
<style>
.ju98ztb3m {
  fill: currentColor;
  d: path("m13.64 18l1.722 1.74q.14.147.153.353t-.16.357q-.159.15-.353.15t-.335-.146l-2.363-2.388q-.242-.243-.242-.566t.242-.565l2.363-2.37q.147-.146.348-.155t.356.136t.15.354t-.14.36L13.64 17h6.303q.213 0 .357.144t.143.357t-.143.356t-.357.143zm-8.428-5.173H4.98q-.31 0-.521-.21q-.21-.21-.21-.52v-.231q0-.311.21-.521t.52-.21h.232q.31 0 .52.21t.21.52v.231q0 .31-.21.52t-.52.211m2.919-.805q-.804-.806-.804-1.945v-4q0-1.14.806-1.945t1.946-.805t1.944.805t.804 1.945v4q0 1.14-.806 1.945t-1.946.805t-1.944-.805m3.182-.705q.514-.511.514-1.24v-4q0-.73-.514-1.24q-.515-.51-1.236-.51t-1.236.51q-.514.51-.514 1.24v4q0 .729.514 1.24q.515.51 1.236.51t1.236-.51");
}

</style>
