<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn4slb1-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-strikethrough-rounded" /></template>
<style>
.hn4slb1-v {
  fill: currentColor;
  d: path("M3.5 13.48q-.213 0-.356-.143Q3 13.193 3 12.98t.144-.356t.356-.143h17q.213 0 .356.144t.144.357t-.144.356t-.356.143zm7.885-2.96V6.25h-4.75q-.257 0-.436-.18q-.18-.18-.18-.438q0-.257.18-.444T6.635 5h10.75q.256 0 .436.18q.179.18.179.438q0 .257-.18.444t-.435.188h-4.75v4.27zm0 4.922h1.25v2.942q0 .257-.18.436q-.18.18-.438.18q-.257 0-.445-.185q-.187-.185-.187-.45z");
}

</style>
