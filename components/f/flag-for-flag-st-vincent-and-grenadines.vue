<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="w6fgolgmi"/><path class="ftktjpg6j"/><path class="xxn7jqb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-st-vincent-and-grenadines" /></template>
<style>
.ftktjpg6j {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M16 6.6C7.6 11.9 2 21.3 2 32s5.6 20.1 14 25.4z");
}

.w6fgolgmi {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("M32 62c5.9 0 11.4-1.7 16-4.6V6.6C43.4 3.7 37.9 2 32 2S20.6 3.7 16 6.6v50.7c4.6 3 10.1 4.7 16 4.7");
}

.xxn7jqb-i {
  fill: var(--svg-color--699635, #699635);
  d: path("M48 57.4c8.4-5.3 14-14.7 14-25.4S56.4 11.9 48 6.6zM24.8 17.9l-6 10.4l6 10.3l6-10.3zm14.4 0l-6 10.4l6 10.3l6-10.3zM26 41.7l6 10.4l6-10.4l-6-10.3z");
}

</style>
