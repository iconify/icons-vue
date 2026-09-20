<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epw4h7jlj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:child-care-sharp" /></template>
<style>
.epw4h7jlj {
  fill: currentColor;
  d: path("M15.051 11.166q.276-.276.276-.666t-.276-.666t-.667-.276t-.666.276t-.276.666t.276.666t.666.276q.391 0 .667-.276m-4.77 0q.277-.276.277-.666t-.276-.666t-.667-.276t-.666.276t-.276.666t.276.666t.666.276t.667-.276m3.94 4.461q1.01-.604 1.624-1.627H8.154q.613 1.023 1.624 1.627q1.01.604 2.222.604t2.222-.604m-5.34 3.747q-1.455-.626-2.542-1.713t-1.714-2.543T4 12t.626-3.118T6.34 6.34t2.542-1.714T12 4t3.118.626T17.66 6.34t1.714 2.542T20 12t-.626 3.118t-1.714 2.542t-2.542 1.714T12 20t-3.118-.626M12.4 8.192q.425 0 .809-.124q.383-.124.383-.468q0-.185-.113-.314q-.113-.128-.279-.128q-.2 0-.359.075t-.441.075q-.64 0-1.099-.459t-.459-1.099q0-.256.02-.395q.02-.14.1-.272q-.245.05-.464.086t-.452.115q-.044.114-.066.233t-.022.233q0 1.01.716 1.726q.717.716 1.726.716");
}

</style>
