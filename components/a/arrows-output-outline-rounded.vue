<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nws-mfoqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrows-output-outline-rounded" /></template>
<style>
.nws-mfoqo {
  fill: currentColor;
  d: path("M12 13.327q-.556 0-.941-.386q-.386-.385-.386-.941t.386-.941t.941-.386t.941.386q.386.385.386.941t-.386.941t-.941.386M5.708 19H8.5q.214 0 .357.143T9 19.5t-.143.357T8.5 20H4.808q-.348 0-.578-.23T4 19.192V15.5q0-.213.143-.357T4.5 15t.357.143T5 15.5v2.792l3.246-3.246q.14-.14.344-.15t.364.15t.16.354t-.16.354zm12.584 0l-3.246-3.246q-.14-.14-.15-.344t.15-.364t.354-.16t.354.16L19 18.292V15.5q0-.213.143-.357T19.5 15t.357.143t.143.357v3.692q0 .349-.23.578t-.578.23H15.5q-.213 0-.357-.143T15 19.5t.143-.357T15.5 19zM5 5.708V8.5q0 .214-.143.357T4.5 9t-.357-.143T4 8.5V4.808q0-.348.23-.578T4.808 4H8.5q.214 0 .357.143T9 4.5t-.143.357T8.5 5H5.708l3.246 3.246q.14.14.15.344t-.15.364t-.354.16t-.354-.16zm14 0l-3.246 3.246q-.14.14-.344.15t-.364-.15t-.16-.354t.16-.354L18.292 5H15.5q-.213 0-.357-.143T15 4.5t.143-.357T15.5 4h3.692q.349 0 .578.23t.23.578V8.5q0 .214-.143.357T19.5 9t-.357-.143T19 8.5z");
}

</style>
