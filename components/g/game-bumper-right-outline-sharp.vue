<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jm7blsbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-bumper-right-outline-sharp" /></template>
<style>
.jm7blsbvl {
  fill: currentColor;
  d: path("m12.89 15.116l2.254.005q.993 0 1.577-.471q.585-.471.585-1.306q0-.628-.35-.99q-.348-.362-1.012-.498v-.031q.564-.117.848-.485q.285-.369.285-.95q0-.819-.571-1.162q-.572-.343-1.725-.343h-1.89zm.85-3.62V9.683h1.026q.736 0 1.089.206q.353.207.353.707q0 .481-.334.69q-.333.21-1.018.21zm0 2.84v-2.09h1.233q.693 0 1.066.263t.372.781q0 .495-.348.776t-1.02.27zM21 4.982v10.73q0 1.362-.973 2.326q-.973.963-2.354.963H6.327q-1.38 0-2.354-.963Q3 17.073 3 15.712V4.98zm-1 1H4v9.73q0 .941.674 1.615T6.327 18h11.346q.979 0 1.653-.674T20 15.712zm0 0H4zM6.99 15.154h.876V12.68h1.169l1.556 2.473h.99l-1.717-2.687q.623-.217.937-.643t.315-1.06q0-.933-.576-1.377t-1.734-.445H6.99zm.856-3.229V9.758h.933q.708 0 1.072.278t.365.783q0 .531-.357.818t-1.009.288z");
}

</style>
