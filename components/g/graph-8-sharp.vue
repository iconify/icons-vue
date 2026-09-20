<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un5nsbb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:graph-8-sharp" /></template>
<style>
.un5nsbb-v {
  fill: currentColor;
  d: path("M7.346 20.98q-.98 0-1.673-.691q-.692-.693-.692-1.674q0-.84.534-1.49q.533-.65 1.331-.816V7.652q-.798-.166-1.331-.816q-.534-.65-.534-1.49q0-.98.692-1.663Q6.366 3 7.346 3t1.673.692t.693 1.674q0 .84-.524 1.48q-.525.64-1.342.806v5.425q.567-.725 1.397-1.16q.83-.436 1.834-.436h1.846q1.346 0 2.279-.962q.933-.961.933-2.307v-.56q-.799-.165-1.323-.806q-.523-.64-.523-1.48q0-.981.682-1.674Q15.654 3 16.634 3q.981 0 1.683.692t.702 1.674q0 .84-.533 1.48q-.534.64-1.352.806v.56q0 1.767-1.231 3.018t-2.98 1.25h-1.846q-1.346 0-2.289.962t-.942 2.327v.54q.818.166 1.342.816t.523 1.49q0 .981-.692 1.674t-1.673.692");
}

</style>
