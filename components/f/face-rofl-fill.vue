<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u2tzrbcky"/><path clip-rule="evenodd" class="ermu2evys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-rofl-fill" /></template>
<style>
.ermu2evys {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.5 12.866L14.95 11.452C15.546 11.107 16.229 11.111 16.786 11.367C17.342 11.623 17.789 12.139 17.916 12.816C18.302 14.884 17.348 16.995 15.5 18.062C13.652 19.129 11.347 18.9 9.749 17.531C9.226 17.083 9.002 16.438 9.059 15.828C9.115 15.218 9.454 14.625 10.05 14.28L12.5 12.866ZM1.879 22.121C1.337 21.579 1 20.828 1 20C1 19.38 1.192 18.775 1.55 18.269L2.775 16.535C3.056 16.137 3.513 15.9 4 15.9C4.487 15.9 4.944 16.137 5.225 16.534L6.45 18.269C6.808 18.775 7 19.38 7 20C7 21.657 5.657 23 4 23C3.172 23 2.421 22.663 1.879 22.121Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u2tzrbcky {
  d: path("M2.075 13.219C2.025 12.814 2 12.407 2 12C2 6.477 6.477 2 12 2C17.523 2 22 6.477 22 12C22 17.523 17.523 22 12 22C11.243 22 10.488 21.914 9.75 21.744M6.719 9.853L8.643 10.185L7.969 12.018M12.781 6.353L12.107 8.185L14.031 8.518");
}

</style>
