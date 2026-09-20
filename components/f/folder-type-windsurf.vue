<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ff50gtb7w"/><path class="dv9l-wjfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-windsurf" /></template>
<style>
.dv9l-wjfg {
  fill: var(--svg-color--0b100f, #0b100f);
  d: path("M29.401 14.903h-.19a1.814 1.814 0 0 0-1.818 1.814v4.056c0 .81-.67 1.466-1.466 1.466a1.52 1.52 0 0 1-1.227-.638l-4.143-5.917a1.84 1.84 0 0 0-1.508-.784c-.945 0-1.795.803-1.795 1.794v4.08a1.47 1.47 0 0 1-1.466 1.466c-.475 0-.947-.238-1.227-.638L9.925 14.98a.187.187 0 0 0-.34.107v3.538c0 .179.055.352.157.5l4.562 6.515c.27.385.668.67 1.126.774a1.803 1.803 0 0 0 2.204-1.748V20.59c0-.81.656-1.466 1.466-1.466h.002c.489 0 .947.238 1.227.638l4.144 5.916a1.81 1.81 0 0 0 3.3-1.01v-4.079c0-.81.657-1.466 1.467-1.466h.162a.183.183 0 0 0 .183-.184v-3.851a.183.183 0 0 0-.183-.184z");
}

.ff50gtb7w {
  fill: var(--svg-color--30e8ba, #30e8ba);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21zm0 4.2h-8.2l1.1-2.1h7.1z");
}

</style>
