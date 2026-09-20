<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gm6wlrb9k"/><path class="ezn96ea8w"/><path class="nb4rxibew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-log" /></template>
<style>
.ezn96ea8w {
  fill: var(--svg-color--00bd02, #00bd02);
  d: path("M2.5 5.5h26.9v1.9H2.5zm8.833 4H19.5v1h-8.167zm0 2.583h12.5v1h-12.5zm0 2.667H21.95v1H11.333zm0 2.833H25.5v1H11.333zm0 2.917h9.834v1h-9.834zm.167 2.583h12.167v1H11.5zM5.5 9.5h4.333v1H5.5zm0 2.583h4.333v1H5.5z");
}

.gm6wlrb9k {
  fill: var(--svg-color--00bd02, #00bd02);
  d: path("M29.4 27.6H2.5V4.5h26.9Zm-25.9-1h24.9V5.5H3.5Z");
}

.nb4rxibew {
  fill: var(--svg-color--00bd02, #00bd02);
  d: path("M5.5 12.083h4.333v1H5.5zm0 2.584h4.333v1H5.5zm0 2.583h4.333v1H5.5zm0 3.25h4.333v1H5.5zm0 2.583h4.333v1H5.5z");
}

</style>
