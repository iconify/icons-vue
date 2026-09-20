<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x228d5b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:label-off-rounded" /></template>
<style>
.x228d5b5u {
  fill: currentColor;
  d: path("M17.733 16.248L6.6 5h8.227q.379 0 .727.165q.348.164.565.462l4.135 5.385q.342.448.342.988t-.342.989zM4.616 19q-.672 0-1.144-.472T3 17.385V6.615q0-.178.043-.349t.11-.312l-2.1-2.1q-.14-.14-.15-.344t.15-.364t.355-.16t.354.16L20.854 22.24q.14.14.153.34t-.153.367q-.16.16-.354.16t-.354-.16l-4.275-4.275q-.115.152-.282.24t-.362.089z");
}

</style>
