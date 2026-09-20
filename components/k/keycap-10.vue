<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="v8o05uu6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:keycap-10" /></template>
<style>
.v8o05uu6s {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M7.213 10.975H5.255C3.663 10.975 3 9.814 3 8.686c0-1.16.829-2.288 2.255-2.288h4.71c1.426 0 2.223 1.028 2.223 2.354v18.875c0 1.658-1.062 2.586-2.488 2.586s-2.487-.928-2.487-2.586zm7.967 7.231C15.18 12.799 17.27 6 23.97 6s8.791 6.799 8.791 12.206s-2.091 12.207-8.791 12.207s-8.79-6.801-8.79-12.207m12.406 0c0-2.521-.232-7.696-3.616-7.696s-3.615 5.175-3.615 7.696c0 2.355.232 7.695 3.615 7.695s3.616-5.339 3.616-7.695");
}

.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
