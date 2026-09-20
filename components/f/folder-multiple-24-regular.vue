<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="koscs6blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-multiple-24-regular" /></template>
<style>
.koscs6blg {
  fill: currentColor;
  d: path("M20.493 8.508a3.25 3.25 0 0 1 1.508 2.742v4a5.75 5.75 0 0 1-5.75 5.75h-8.5a3.25 3.25 0 0 1-2.743-1.508q.12.008.243.008h11a4.25 4.25 0 0 0 4.25-4.25v-6.5q0-.122-.008-.242M7.406 3c.572 0 1.126.217 1.543.618A54 54 0 0 1 10.825 5.5h5.426A3.25 3.25 0 0 1 19.5 8.75v6.5a3.25 3.25 0 0 1-3.25 3.25h-11A3.25 3.25 0 0 1 2 15.25v-9A3.25 3.25 0 0 1 5.25 3zm3.42 4a54 54 0 0 1-1.877 1.882c-.417.4-.971.618-1.543.618H3.5v5.75c0 .966.784 1.75 1.75 1.75h11A1.75 1.75 0 0 0 18 15.25v-6.5A1.75 1.75 0 0 0 16.251 7zM5.25 4.5A1.75 1.75 0 0 0 3.5 6.25V8h3.906a.73.73 0 0 0 .504-.2a59 59 0 0 0 1.564-1.55A59 59 0 0 0 7.91 4.7a.73.73 0 0 0-.504-.2z");
}

</style>
