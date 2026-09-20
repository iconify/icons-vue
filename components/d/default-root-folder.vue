<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zghy_mbjo"/><path class="jxzdurb2m"/><path class="qlahy-byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:default-root-folder" /></template>
<style>
.jxzdurb2m {
  fill: var(--svg-color--c09553, #c09553);
  d: path("M19.735 31.25h-5.924l9.794-21.5h5.985z");
}

.qlahy-byj {
  fill: var(--svg-color--ffeebe, #ffeebe);
  d: path("M23.766 10H29.2l-9.625 21H14.2Z");
}

.zghy_mbjo {
  fill: var(--svg-color--c09553, #c09553);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

</style>
