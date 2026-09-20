<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="bcbd4kbym"/><path class="x_24cibik"/><path class="e6y9sw2be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:leftwards-pushing-hand-dark-skin-tone" /></template>
<style>
.bcbd4kbym {
  fill: var(--svg-color--583529, #583529);
  d: path("M16.5 31c-.64 0-1.28-.24-1.77-.73C9.28 24.82 6.79 5.49 6.52 3.3C6.35 1.93 7.33.68 8.7.52c1.38-.17 2.62.81 2.78 2.18c.93 7.6 3.59 20.84 6.79 24.04a2.499 2.499 0 0 1-1.77 4.27Z");
}

.e6y9sw2be {
  fill: var(--svg-color--583529, #583529);
  d: path("M12.21 26.47c-.77-1.68-1.11-3.93-1.47-5.82c-.22-1.26-.42-2.55-.6-3.81c-.05-1.6-1.43-2.97-3.04-2.74c-.47.01-.92.11-1.35.26l.02.86c1.24-.57 2.76-.43 3.19 1.06c.44 3.71.43 7.3 1.67 10.9c.47 1.09 2.09.36 1.59-.71ZM26.55 34H13.33c-1.55 0-3.09-.15-4.61-.46l-2.04-.41a7.56 7.56 0 0 0 5.49 2.35h16.51c1.25 0 2.3-.84 2.64-1.98c-1.57.32-3.16.5-4.76.5Z");
}

.x_24cibik {
  fill: var(--svg-color--7c533e, #7c533e);
  d: path("m28.9 25.33l-8.75 1.15c-2.15.51-3.94-1.06-5.01-2.8l-.17-.38c-1.3-2.86-2.22-5.87-2.73-8.97L10.32 2.64a2.392 2.392 0 0 0-4.77.31l.22 12.21c0 .07-.02.14-.05.21c-.78 1.3-1.35 3.72.04 7.88c-.15.77-.44 1.48-.92 2.69c-1.28 4.82 2.35 9.55 7.34 9.55h16.51a2.76 2.76 0 0 0 2.76-2.76v-5.16c0-1.35-1.19-2.4-2.54-2.22Z");
}

</style>
