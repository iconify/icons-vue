<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dywv8abul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-codeclimate" /></template>
<style>
.dywv8abul {
  fill: var(--svg-color--0b2734, #0b2734);
  d: path("M20.745 8.2L15.4 13.517l3.173 3.173l2.174-2.174l6.111 6.14L30 17.484Zm-6.317 6.287l-3.144-3.143l-8.05 8.05L2 20.627L5.173 23.8l1.234-1.263l4.084-4.055l.793-.793l3.144 3.144L17.4 23.8l3.173-3.173L17.6 17.66z");
}

</style>
