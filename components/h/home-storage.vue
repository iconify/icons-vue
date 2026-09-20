<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugwy7tbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home-storage" /></template>
<style>
.ugwy7tbwv {
  fill: currentColor;
  d: path("m5.846 19.385l-1.673-10h15.654l-1.673 10zm4.154-5.5h4q.213 0 .356-.144q.144-.144.144-.357t-.144-.356t-.356-.144h-4q-.213 0-.356.145t-.144.356t.144.356t.356.143M6 8q-.213 0-.356-.144T5.5 7.499t.144-.356T6 7h12q.213 0 .356.144t.144.357t-.144.356T18 8zm2-2.384q-.213 0-.356-.144T7.5 5.115t.144-.356q.143-.144.356-.144h8q.213 0 .356.144t.144.357t-.144.356t-.356.144z");
}

</style>
