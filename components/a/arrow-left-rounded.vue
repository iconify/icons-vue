<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6knt7jxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-left-rounded" /></template>
<style>
.p6knt7jxa {
  fill: currentColor;
  d: path("m12.804 15.112l-2.677-2.677q-.093-.093-.143-.2T9.935 12t.05-.235t.143-.2l2.677-2.677q.056-.055.129-.093q.073-.037.157-.037q.168 0 .289.11q.121.112.121.293v5.677q0 .182-.124.293t-.288.111q-.042 0-.284-.13");
}

</style>
