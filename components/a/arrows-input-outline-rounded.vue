<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-g0tub0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrows-input-outline-rounded" /></template>
<style>
.i-g0tub0b {
  fill: currentColor;
  d: path("M12 13.327q-.556 0-.941-.386q-.386-.385-.386-.941t.386-.941t.941-.386t.941.386q.386.385.386.941t-.386.941t-.941.386m-4 3.38l-3.246 3.247q-.14.14-.344.15t-.364-.15t-.16-.354t.16-.354L7.292 16H4.5q-.213 0-.357-.143T4 15.5t.143-.357T4.5 15h3.692q.348 0 .578.23t.23.578V19.5q0 .214-.143.357T8.5 20t-.357-.143T8 19.5zm8 0V19.5q0 .214-.143.357T15.5 20t-.357-.143T15 19.5v-3.692q0-.349.23-.578t.578-.23H19.5q.214 0 .357.143T20 15.5t-.143.357T19.5 16h-2.792l3.246 3.246q.14.14.15.345q.01.203-.15.363t-.354.16t-.354-.16zM7.292 8L4.046 4.754q-.14-.14-.15-.344t.15-.364t.354-.16t.354.16L8 7.292V4.5q0-.213.143-.357T8.5 4t.357.143T9 4.5v3.692q0 .348-.23.578T8.192 9H4.5q-.213 0-.357-.143T4 8.5t.143-.357T4.5 8zm9.416 0H19.5q.214 0 .357.143T20 8.5t-.143.357T19.5 9h-3.692q-.349 0-.578-.23T15 8.192V4.5q0-.213.143-.357T15.5 4t.357.143T16 4.5v2.792l3.246-3.246q.14-.14.345-.15q.203-.01.363.15t.16.354t-.16.354z");
}

</style>
