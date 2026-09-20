<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iu_nnhp_h"/><path class="aln4x0b_g"/><path class="ij53u-8fc"/><path class="ta-ettb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-velocity" /></template>
<style>
.aln4x0b_g {
  fill: var(--svg-color--262692, #262692);
  d: path("m29.132 8.551l-3.681-2.02v.943h-9.63v1.95h9.63v1.147z");
}

.ij53u-8fc {
  fill: var(--svg-color--262693, #262693);
  d: path("m8.984 2l-2.02 3.687h.942v9.641h1.951V5.687h1.147zm14.721 28l-2.02-3.757h.943v-9.826h1.95v9.826h1.147z");
}

.iu_nnhp_h {
  d: path("M16.245 24.187a8.352 8.352 0 1 1 8.355-8.352a8.36 8.36 0 0 1-8.355 8.352m0-14.762a6.41 6.41 0 1 0 6.41 6.41a6.417 6.417 0 0 0-6.41-6.41");
}

.ta-ettb5j {
  fill: var(--svg-color--262692, #262692);
  d: path("m2.868 23.32l3.766-2.02v.942h9.85v1.95h-9.85v1.148z");
}

</style>
