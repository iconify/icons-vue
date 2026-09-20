<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="axp7_8b3t"/><path class="p6poerb5q"/><path class="wh2j5zh_f"/><path class="h-8htzbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:chopsticks" /></template>
<style>
.axp7_8b3t {
  fill: var(--svg-color--d61029, #d61029);
  d: path("m87.586 12.477l-82.8 98.484c-.35.459-.722.978-.637 1.48c.183 1.083 3.47 3.811 4.42 3.88c.785.056 1.154-.317 1.68-.907l77.274-86.749z");
}

.h-8htzbfm {
  fill: var(--svg-color--474c4f, #474c4f);
  d: path("M121.452 28.648c-2.152-2.537-3.155-3.665-4.228-3.569c-1.073.086-21.199 18.343-21.199 18.343l6.9 7.601s20.877-17.173 20.936-18.387c.048-1.002-.659-1.915-2.41-3.988");
}

.p6poerb5q {
  fill: var(--svg-color--474c4f, #474c4f);
  d: path("M95.49 4.002c-1.214.06-18.387 20.936-18.387 20.936l7.601 6.9s18.257-20.126 18.343-21.199c.096-1.073-1.032-2.076-3.569-4.227c-2.073-1.751-2.986-2.458-3.988-2.41");
}

.wh2j5zh_f {
  fill: var(--svg-color--d61029, #d61029);
  d: path("m99.198 40.603l-86.749 77.274c-.576.485-1.008.953-.906 1.68c.131.943 2.799 4.222 3.88 4.42c.677.124 1.074-.278 1.48-.637l98.483-82.8z");
}

</style>
