<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s42_hlb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:eyebrow" /></template>
<style>
.s42_hlb0w {
  fill: currentColor;
  d: path("M14.923 13.558q-1.048 0-2.18.176q-1.132.177-2.347.485t-2.514.721t-2.674.893q-.256.086-.495.126q-.24.041-.463.041q-1.02 0-1.74-.663q-.721-.664-.721-1.587v-2.267q0-.806.559-1.432q.56-.626 1.418-.768q1.742-.312 3.359-.549q1.617-.236 3.035-.395q1.417-.158 2.631-.249Q14.006 8 14.942 8q2.966 0 4.88 1.949q1.915 1.949 2.376 5.435q.03.16-.07.289q-.101.129-.266.196q-.14.067-.296.046q-.156-.02-.316-.144q-1.523-1-3.294-1.607t-3.033-.606");
}

</style>
