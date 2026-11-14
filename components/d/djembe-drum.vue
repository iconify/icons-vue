<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nygcsgmes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:djembe-drum" /></template>
<style>
.nygcsgmes {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q-7.748 0-7.75 3.249V5q0 2.941 3.087 6.148q1.489 1.547 1.651 2.326L7.267 21.34q-.015.072-.017.146q-.001.074.012.146q.013.073.04.142t.067.131q.039.062.091.115q.051.053.112.096q.06.042.128.071q.068.03.14.046q.079.017.16.017h8q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.081-.017-.16l-1.721-7.866q.162-.779 1.651-2.326Q19.75 7.941 19.75 5q0-3.25-7.75-3.25m-3.582 8.357q-1.28-1.329-1.946-2.558Q8.4 8.25 12 8.25t5.528-.701q-.666 1.229-1.946 2.558q-1.949 2.026-2.078 3.318q-.012.119.013.235l1.551 7.09H8.932l1.551-7.09q.025-.116.013-.235q-.129-1.292-2.078-3.318");
}

</style>
