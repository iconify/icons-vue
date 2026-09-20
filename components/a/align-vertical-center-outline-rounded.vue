<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk7ogrkbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-vertical-center-outline-rounded" /></template>
<style>
.pk7ogrkbp {
  fill: currentColor;
  d: path("M7.899 19.697q-.303-.303-.303-.716V12.5H3.5q-.213 0-.357-.143T3 12t.143-.357t.357-.143h4.096V5.02q0-.414.303-.717T8.616 4t.716.303t.303.716V11.5h4.73V8.02q0-.414.303-.717T15.385 7t.716.303t.303.716V11.5H20.5q.214 0 .357.143T21 12t-.143.357t-.357.143h-4.096v3.48q0 .414-.303.717t-.716.303t-.717-.303t-.302-.716V12.5H9.635v6.48q0 .414-.303.717T8.616 20t-.717-.303");
}

</style>
