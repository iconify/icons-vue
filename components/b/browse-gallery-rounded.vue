<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwurp0c3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:browse-gallery-rounded" /></template>
<style>
.kwurp0c3h {
  fill: currentColor;
  d: path("M9.5 11.812V8q0-.213-.143-.357T9 7.5t-.357.143T8.5 8v3.86q0 .161.056.3q.056.14.186.27l2.723 2.724q.14.14.345.13q.203-.009.344-.15t.14-.343q0-.204-.14-.345zM22 12q0-1.916-.943-3.52t-2.591-2.536q-.197-.11-.264-.307q-.067-.198.012-.4q.084-.208.302-.256t.413.061q1.873 1.09 2.972 2.933T23 12t-1.099 4.025t-2.953 2.933q-.196.128-.413.07q-.218-.057-.321-.264q-.098-.202-.022-.4t.274-.308q1.648-.931 2.59-2.536T22 12M5.882 19.374q-1.455-.626-2.542-1.713t-1.714-2.543T1 12t.626-3.118T3.34 6.34t2.542-1.714T9 4t3.118.626T14.66 6.34t1.714 2.542T17 12t-.626 3.118t-1.714 2.542t-2.542 1.714T9 20t-3.118-.626");
}

</style>
