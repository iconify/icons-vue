<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ml_bmxbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:image-border-28-filled" /></template>
<style>
.ml_bmxbbm {
  fill: currentColor;
  d: path("M12.586 14.586L8 19.172V8h12v11.172l-4.586-4.586a2 2 0 0 0-2.828 0M17 9.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m-2.646 6.146L18.707 20H9.293l4.353-4.354a.5.5 0 0 1 .708 0M3 6.75A3.75 3.75 0 0 1 6.75 3h14.5A3.75 3.75 0 0 1 25 6.75v14.5A3.75 3.75 0 0 1 21.25 25H6.75A3.75 3.75 0 0 1 3 21.25zm4.25-.25a.75.75 0 0 0-.75.75v13.5c0 .414.336.75.75.75h13.5a.75.75 0 0 0 .75-.75V7.25a.75.75 0 0 0-.75-.75z");
}

</style>
