<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w00274xxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-vertical-top-outline-rounded" /></template>
<style>
.w00274xxo {
  fill: currentColor;
  d: path("M7.995 20.197q-.303-.303-.303-.716V8.077q0-.413.303-.716t.717-.303t.716.303q.303.303.303.716v11.404q0 .413-.303.716t-.717.303t-.716-.303m6.577-6q-.303-.303-.303-.716V8.077q0-.413.303-.716t.717-.303t.716.303q.303.303.303.716v5.404q0 .413-.303.716t-.716.303t-.717-.303M3.5 4.481q-.213 0-.357-.143T3 3.98t.143-.357t.357-.143h17q.214 0 .357.143T21 3.98t-.143.357t-.357.143z");
}

</style>
