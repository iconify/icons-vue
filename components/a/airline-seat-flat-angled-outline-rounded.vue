<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyry_uqun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airline-seat-flat-angled-outline-rounded" /></template>
<style>
.jyry_uqun {
  fill: currentColor;
  d: path("m9.977 11.333l1.087-2.962q.159-.41.534-.596t.785-.027l6.479 2.361q1.17.422 1.707 1.544t.097 2.293l-.425 1.125q-.131.304-.43.46t-.601.025l-8.748-3.192q-.323-.131-.47-.42q-.146-.288-.015-.611m2.039-2.666q-.2.5-.344.957t-.337.938l-.345.925zm6.534 9.58l-14.963-5.44q-.189-.067-.274-.259t-.019-.38t.263-.278t.384-.015l14.963 5.438q.188.068.274.26t.018.38q-.067.19-.262.278q-.196.088-.384.015M5.287 10.242q-.616-.615-.616-1.48q0-.866.616-1.481q.615-.616 1.48-.616q.866 0 1.481.616q.616.615.616 1.48q0 .866-.616 1.481q-.615.616-1.48.616q-.866 0-1.481-.616m2.26-.7q.317-.317.317-.78t-.317-.78t-.78-.317t-.78.317t-.316.78t.317.78t.78.316t.779-.317m3.444 1.945l8.392 3.062l.33-.95q.275-.8-.072-1.54t-1.127-1.016l-6.498-2.375zm-4.204-2.7");
}

</style>
