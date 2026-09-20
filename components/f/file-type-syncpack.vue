<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="yjvf9utul"><path id="SVGYX9iMblc" class="p5k919b0j"/></g><use href="#SVGYX9iMblc" transform="rotate(180 16 16)" class="k9e5u9q8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-syncpack" /></template>
<style>
.k9e5u9q8v {
  fill: var(--svg-color--365314, #365314);
}

.p5k919b0j {
  d: path("M2 13.15h2.5C7-.1 26 .6 27.7 13.7l-3.6-4l-2.7 3.25C19 7.5 12 9 10.7 13.15h2.95L7.8 20");
}

.yjvf9utul {
  fill: var(--svg-color--84cc16, #84cc16);
}

</style>
