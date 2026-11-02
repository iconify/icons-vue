<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o_ktexcbd"/><path class="m0cikccuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bear-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m0cikccuw {
  d: path("M9.01 11a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2ZM13 15a1.002 1.002 0 0 1 .707 1.707l-1 1a1 1 0 0 1-1.414 0l-1-1A1 1 0 0 1 11 15Z");
}

.o_ktexcbd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.822 8.993C3.052 7.457 3.542 5.719 4.9 4.7a3.7 3.7 0 0 1 1.131-.581c.42-.133.863-.183 1.302-.147a3.33 3.33 0 0 1 1.911.823c1.818-.723 3.694-.723 5.512 0a3.33 3.33 0 0 1 1.911-.823c.868-.072 1.74.208 2.433.728c1.358 1.019 1.848 2.757 1.078 4.293c.78 1.31 1.304 2.769 1.443 4.291c.127 1.395-.079 2.834-.695 4.099C19.602 21.219 15.592 21.999 12 22c-3.592-.001-7.602-.781-8.926-4.617c-.616-1.265-.822-2.704-.695-4.099c.139-1.522.663-2.981 1.443-4.291");
}

</style>
